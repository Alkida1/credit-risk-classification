# credit-risk-classification


## Overview

This analysis aimed to develop and evaluate machine learning models for predicting loan default risk. The dataset used in this analysis contained various features related to loan applicants, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable was the loan status, indicating whether a loan is healthy (0) or has a high-default- risk  (1). The goal was to build models to accurately classify loans and provide insights into the factors contributing to loan default risk.

## Results

The following machine learning models were trained and evaluated:
Logistic Regression Model:
Accuracy Score: 0.99
Precision Score:
Class 0 (healthy loan): 1.00
Class 1 (high-risk loan): 0.84
Recall Score:
Class 0 (healthy loan): 0.99
Class 1 (high-risk loan): 0.99

## Summary

The logistic regression model demonstrated excellent performance in predicting healthy and high-risk loans. It achieved high accuracy, precision, and recall scores for both classes. The model accurately classified 99% of the loans in the dataset, with a precision of 1.00 for healthy loans and 0.84 for high-risk loans. The recall score of 0.99 indicates that the model correctly identified 99% of healthy and high-risk loans.
Based on these results, we recommend the logistic regression model for use. It provides a reliable means of identifying loans with high default risk. In addition, the model's high precision score for healthy loans ensures minimal false positives, reducing the potential loss of profitable loan opportunities.
