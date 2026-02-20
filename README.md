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

The dataset is available from GESIS – Leibniz Institute for the Social Sciences:
https://www.gesis.org/en/issp/data-and-documentation/family-and-changing-gender-roles/2022

Due to licensing restrictions, raw microdata are not included in this repository.
To reproduce the analysis, please download the dataset directly from GESIS after registration.

The analysis includes data cleaning, weighted descriptive statistics, visualization, and multivariate regression modeling.

## 📬 Contact

If you would like to discuss this project or potential collaboration opportunities, feel free to contact me:

- Email: marcin.deszczka at gmail.com
- LinkedIn:https://www.linkedin.com/in/marcin-deszczka-407b113a9/
