# Module 12 Report Template

## Overview of the Analysis

This repository has Python code aimed at evaluating the efficacy of machine learning in predicting borrower creditworthiness through financial data analysis. It involves loading financial data, splitting it into training and testing sets, training a logistic regression model, making predictions, and assessing model performance using a confusion matrix and classification report.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Logistic Regression Model: 
- Accuracy: 99% Indicates the model correctly predicts 99% of loans.
- Precision: Healthy Loans: 100% High-risk Loans: 84% Shows the model's correctness when predicting healthy loans is 100%, and for high-risk loans, it's 84%.
- Recall: Healthy Loans: 99% High-risk Loans: 94% Shows that 99% of healthy loans and 91% of high-risk loans were correctly identified.

## Summary

The logistic regression model performs very well overall, with high accuracy, precision, and recall rates. It excels in correctly predicting healthy loans 100% of the time. However, its prediction capability for high-risk loans is slightly lower at 84%, indicating that 16% of predicted high-risk loans were actually healthy. Despite this, the model is still suitable for evaluating creditworthiness.
