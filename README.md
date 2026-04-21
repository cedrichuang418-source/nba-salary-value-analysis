# 🏀 NBA Player Salary vs. Performance Value Analysis (2023)

> Quantifying on-court value per dollar, identifying market inefficiencies, and exploring optimal salary-performance ratios.

Project Overview

This is a simple analysis project for NBA Salary vs. Performance, focusing on evaluating whether player salaries match their on-court output.

File Structure

• nba-salary-value-analysis.ipynb: Main analysis code

• nba_salaries_2023.csv: Dataset (includes adjusted salary and performance stats)

How to Run

1. Ensure nba_salaries_2023.csv is in the same folder as the notebook.

2. Open in Jupyter Notebook/JupyterLab and run cells step-by-step.

Key Features

• Data preprocessing (clean missing values, standardize salary)

• Calculate Points per Million to measure value for money

• Visualize relationships (scatter plots, histograms)

• Correlation & linear regression analysis

Core Insights

• Salary and performance have a moderate positive correlation.

• Some low-salary players offer better value than high-salary counterparts.

• The Points per Million metric helps identify undervalued players for contract decisions.

Dependencies

• Python 3.8+

• Required packages: pandas, numpy, matplotlib, scikit-learn
pip install pandas numpy matplotlib scikit-learn
