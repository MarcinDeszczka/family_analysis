# family_analysis
<h1 align="center">This project analyzes survey data from the International Social Survey Programme (ISSP 2022) to examine preferences regarding the ideal number of children.</h1>

**Dataset:**
- 45,762 respondents
- 32 countries
- Weighted survey data (WEIGHT_COM)

**Tools:**
- Python (pandas, numpy)
- statsmodels (Weighted Least Squares regression)
- matplotlib / seaborn

**Key findings:**
- The most frequently chosen ideal number of children is 2 (~56% of respondents).
- Country is the strongest predictor of declared ideal number of children (R² ≈ 0.13).
- Sex is not statistically significant.
- Age has a statistically significant but practically small effect.

The analysis includes data cleaning, weighted descriptive statistics, visualization, and multivariate regression modeling.
