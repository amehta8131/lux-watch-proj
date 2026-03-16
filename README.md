# Watch Secondary Market Analysis

## Overview
An exploratory data analysis and machine learning project analyzing 9,777 watches across 14 brands on the secondary market. The goal of this project is to uncover pricing trends, identify value drivers, and build a model that predicts resale prices based on watch characteristics.

## Dataset
- 9,777 watches
- 14 brands including Cartier, IWC, TAG Heuer, Seiko, and Longines
- Features include brand, model, price, movement type, case material, bracelet material, condition, and year of production
- Source: Secondary watch market platform

## Tools & Technologies
- Python
- SQL (pandasql)
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- XGBoost

## Project Structure
```
├── Watches_cleaned.xlsx        # Cleaned dataset
├── watches_analysis.ipynb      # Main analysis notebook
└── README.md                   # Project documentation
```

## Business Questions Answered
1. Which brands command the highest average price on the secondary market?
2. Does watch condition impact resale price?
3. Which movement type tends to be most expensive?
4. What are the most popular case and bracelet materials?
5. Does case material influence price?
6. What is the price distribution across all watches?

## Key Findings
- IWC commands the highest average resale price while Seiko has the lowest
- Unworn watches fetch significantly higher resale prices than used ones
- Manual winding movements tend to be the most expensive
- Steel is the most popular case and bracelet material
- Precious metal cases command significantly higher prices than steel
- IWC and Cartier retain the highest resale value for older watches
- The majority of secondary market listings in this data set are priced under $5,000

## Machine Learning Model
Built three regression models to predict watch resale price:
- Linear Regression (baseline)
- Random Forest
- XGBoost

Features used: brand, movement, case material, bracelet material, condition, year of production

## How to Run
1. Clone the repository
2. Open watches_analysis.ipynb in Google Colab or Jupyter Notebook
3. Update the dataset URL in Section 1 with your own raw GitHub link
4. Run all cells in order

## Author
Aakash Mehta  
[LinkedIn](https://www.linkedin.com/in/aakash-mehta-20772a261/) | [GitHub](https://github.com/amehta8131)
