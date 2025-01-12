# Investigating Determinants of Charitable Giving to Paralyzed Veterans

## Project Overview
This project examines factors influencing the dollar amount of the most recent charitable gifts made to paralyzed veterans in the United States. Using regression analysis and two-way ANOVA, the study identifies key predictors and explores interactions between demographic and socio-economic variables. The findings aim to provide actionable insights for improving fundraising strategies.

## Key Highlights
- **Dataset**: Derived from the KDD Cup 1998 dataset, consisting of 95,412 observations and 7 variables after data wrangling
- **Primary Objective**: Identify significant predictors of charitable giving and understand how they interact to affect donation amounts
- **Statistical Methods**: Multiple Linear Regression (MLR), Two-Way ANOVA, Tukey's HSD, and nested F-tests

## Methodology
### Data Preparation
- Variables selected: `FEDGOV`, `LOCALGOV`, `MAXADATE`, `NUMPROM`, `DOMAIN`, `GENDER`, and `LASTGIFT`.
- Data transformations:
  - Log transformation of `LASTGIFT` to address skewness.
  - Grouping categorical levels in `DOMAIN` for simplicity.
  - Removal of rows with missing or inconsistent values.

## Limitations
- Residuals exhibited minor deviations from normality
- Low R-squared values indicate limited explanatory power of the predictors

## References
- KDD Cup 1998 dataset: [KDD Data](https://kdd.ics.uci.edu/databases/kddcup98/kddcup98.html).
