# Analysis of Graduate Labor Force Participation in India (2023-24)

-  India-Graduate-Labor-Analysis-2024
### Tools Used
- MOSPI e-Sankhyiki Portal (Data Extraction)
- MS Excel (Bivariate Regression & Visualisation)
- PYTHON (paired sample t-test)
- jamovi (paired t-test, shapiro-wilk test:test for normality, Q-Q plot, wilcoxon rank test)

### Project Overview
This project investigates the relationship between Male and Female Graduate Labour Force Participation Rates (LFPR) across 36 Indian States and UTs using the latest MOSPI PLFS data.

### Key Statistical Results(bivariate regression & visualisation)
- **Correlation ($r$):** 0.52 (Moderate Positive)
- **R-Squared ($R^2$):** 0.2699
- **P-Value:** 0.0011 (Highly Statistically Significant)
- **Standard Error:** 1.63

  ### Conclusion
  While a significant national trend exists, 73% of the variance in female graduate participation is driven by state-specific factors      rather than general male employment trends, highlighting regional socio-economic disparities.

## paired t test using python to validate my results
to validate my findings on gender disparity , I conducted a **paired sample t-test** using **scipy.stats** library in python

-**null hypothesis:** There is no signigficant difference between male and female graduate participation in workforce

-**alternative hypothesis:** There is a significant difference between male and female graduate participation in workforce
 ## results
 - **t-statistic:** 14.98676
 - **p-value:** 8.4536e-17
 ## conclusion
 the p-value is less than 0.05(<0.05) leading to the rejection of null hypothesis so we conclude that there is a significant difference   between male and female graduate participation in workforce.

## running paired t-test, wilcoxon test to validate my results
to further validate my findings on gender disparity in workforce, I conducted **paired sample t-test** as well as **wilcoxon test**(non-parametric) using jamovi
 ## results
 - **t-statistic:** 15.0
 - **wilcoxon rank test:** 666
 - **p-value:** <0.001
 -  **Q-Q plot:** (Q-Q_plot.png)
 -  
 -  
