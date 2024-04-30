# The-Financial-analysis-using-classification-Models

# Predictive Analysis of Loan Defaults

# Overview

This project, conducted by Jiwon Stella Mok (G01096224), investigates factors leading to loan defaults using data from over 4,000 customers of the National Bank. The primary aim is to employ machine learning algorithms to predict the likelihood of applicants defaulting on loans. This analysis is crucial for minimizing financial losses due to defaults and improving the bank's lending processes.

# Repository Contents

R Scripts: Contains all scripts used for data analysis and model building.
Data: Directory with the loan data file loan_data.rds.
Models: Folder with saved models and their performance metrics.

# Summary of Results

- The analysis highlights several key findings:

Significant Predictors: Interest rate, annual income, and loan term significantly affect the default rate.
Insignificant Factors: History of bankruptcy, debt-to-income ratio, and home ownership do not significantly influence the default rate.
Model Performance

- Three models were developed:

Logistic Regression
Random Forest
LDA (Linear Discriminant Analysis)
All models demonstrated high accuracy, with ROC AUC values of 99%, 97.6%, and 99% respectively. The logistic regression model, in particular, showed that loan interest rate and term are crucial predictors of default.

# Recommendations

Shorten Loan Terms: Reduce loan terms from 5 years to 3 years to decrease the default rate.
Target Higher Income Applicants: Prioritize applicants with higher annual incomes, as they are less likely to default.
Lower Interest Rates: Decrease interest rates to reduce default rates; particularly, rates above 10% have shown a high correlation with defaults.
Conclusion

The project effectively identifies key factors influencing loan defaults and provides actionable recommendations to minimize risk. These insights will assist the bank in refining its loan approval criteria and optimizing financial outcomes.

# Appendix

Detailed analysis including code snippets for data preprocessing, model training, evaluation, and visualization is provided in the R scripts within this repository.
