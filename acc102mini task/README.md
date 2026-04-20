{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "740b7fce-b017-428e-9667-1f8b2eb0dc61",
   "metadata": {},
   "source": [
    "# NBA Player Salary vs. Performance Value Analysis (2023)\n",
    "\n",
    "This project analyzes the relationship between NBA player salaries and their on-court performance for the 2023 season to identify high-value players and potential market inefficiencies.\n",
    "\n",
    "![NBA Salary vs Performance](nba_salary_vs_performance.png)\n",
    "\n",
    "## Overview\n",
    "\n",
    "The analysis constructs a composite \"Performance Score\" from key statistics and uses it to calculate a \"Value Score\" (Performance per $1M of salary). The findings reveal a moderate positive correlation between pay and performance, with significant value disparities even among the highest-paid players.\n",
    "\n",
    "## Key Findings\n",
    "\n",
    "- **Moderate Correlation**: There is a moderate positive correlation (r = 0.51) between player salary and performance.\n",
    "- **Best Value Tier**: The `>$30M` salary tier offers the best average value for money.\n",
    "- **Market Inefficiencies**: The analysis identified players who are potential bargains (high performance, low salary) and others who may be overpaid (low performance, high salary).\n",
    "\n",
    "## Files\n",
    "\n",
    "- `acc102product.ipynb`: The main Jupyter Notebook containing all code, analysis, and visualizations.\n",
    "- `nba_salary_vs_performance.png`: Scatter plot of salary vs. performance, colored by value score.\n",
    "- `performance_by_salary_tier.png`: Bar chart showing average performance by salary tier.\n",
    "\n",
    "## Requirements\n",
    "\n",
    "To run this analysis, you will need the following Python libraries:\n",
    "- pandas\n",
    "- numpy\n",
    "- matplotlib\n",
    "- seaborn\n",
    "- scikit-learn\n",
    "\n",
    "You can install them using pip:\n",
    "```bash\n",
    "pip install pandas numpy matplotlib seaborn scikit-learn"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8f8c88be-30e8-4f45-940c-f192ceacd5bf",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:base] *",
   "language": "python",
   "name": "conda-base-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
