# 🎬 Movie Industry Analysis

## 📌 Project Description
This project analyzes a dataset from the film industry containing data on more than 7,000 movies between 1980 and 2020.
The main objective is to determine which factors (budget, company, director, genre, etc.) have the strongest correlation with a movie's financial success.

### The dataset was downloaded from Kaggle.

## 🛠️ Technologies Used
*   **Python** (3.x)
*   **Pandas** (Data cleaning and manipulation)
*   **Seaborn / Matplotlib** (Data visualization)
*   **NumPy** (Statistical calculations)

## 📊 Key Findings
1.  Budget has the highest correlation (0.74) compared to gross. Kendall's robust method ranks popularity (0.55) above investment (0.51),
suggesting that while money helps, the real return comes from generating hype and moving large audiences.
This suggests that financial investment in production and marketing is the most reliable predictor of commercial success.

2.  **Popularity matters:** The number of votes on review platforms has a very high correlation (0.61) with financial success, suggesting that hype is a vital predictor.

3. Contrary to popular belief, the production company has a very low correlation with financial success. The studio brand does not guarantee success.



## 📷 
![Budget vs Gross](budget_vs_gross_analysis.png)

![Correlation matrix](Correlation_matrix.png)


## 🚀 How to run this project
1.  Clone the repository:
```bash
git clone https://github.com/Vicksdev2/movie-correlation-project.git
```
2.  Install the dependencies:
```bash
pip install pandas seaborn matplotlib numpy
```
3.  Open the `movie_correlation_project.ipynb` file in Jupyter Notebook or VS Code.

## ✒️ Author
Victoria
