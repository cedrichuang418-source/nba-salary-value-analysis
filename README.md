# 🏀 NBA Player Salary vs. Performance Value Analysis (2023)

> Quantifying on-court value per dollar, identifying market inefficiencies, and exploring optimal salary-performance ratios.

## 🔍 Overview
This project analyzes the relationship between NBA player salaries and their on-court performance for the 2023 season. We construct a composite **Performance Score** and derive a **Value Score** (performance per $1M salary) to identify:
- High-value players (strong performance, reasonable pay)
- Potential bargains & overpaid players
- Market inefficiencies across salary tiers

## 📊 Key Findings
- Moderate positive correlation between salary and performance (**r = 0.51**)
- The **>$30M salary tier** offers the best average value for money
- Identified notable bargains (e.g., high-performing mid-tier players) and overpaid stars

## 📁 Files
- [`acc102product.ipynb`](acc102mini%20task/acc102product.ipynb) — Full analysis notebook (code, visualizations, methodology)
- [`nba_salary_vs_performance.png`](acc102mini%20task/nba_salary_vs_performance.png) — Scatter plot: salary vs. performance (colored by value score)
- [`performance_by_salary_tier.png`](acc102mini%20task/performance_by_salary_tier.png) — Bar chart: avg. performance by salary tier

## ⚙️ Requirements
Python 3.9+ with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
