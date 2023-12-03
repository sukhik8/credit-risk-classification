# credit-risk-classification
## Overview of the Analysis

Purpose of the Analysis: The purpose of this analysis is to evaluate and compare the performance of two machine learning models in predicting loan status (healthy or high-risk) based on financial information.

Financial Information: The data includes information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (0 for healthy loan, 1 for high-risk loan).

Variables to Predict: The main variable to predict is the loan_status (healthy or high-risk loan).

Stages of the Machine Learning Process:

Data Preprocessing: Cleaning and organizing the data for analysis.
Exploratory Data Analysis (EDA): Understanding the distribution and relationships within the data.
Model Training: Training two logistic regression models using different datasets.
Model Evaluation: Evaluating the models using metrics like accuracy, precision, and recall.
Comparison: Comparing the performance of the two models.
Methods Used: Method 1: LogisticRegression Method 2: RandomOverSampler

## Results

### Machine Learning Model 1:

Accuracy: 99%
Precision (healthy): 100%
Precision (high-risk): 85%
Recall (healthy): 99%
Recall (high-risk): 91%
F1-Score (healthy): 100%
F1-Score (high-risk): 88%
### Machine Learning Model 2:

Accuracy: 99.37%
Precision (healthy): 100%
Precision (high-risk): 84%
Recall (healthy): 99%
Recall (high-risk): 99%
F1-Score (healthy): 100%
F1-Score (high-risk): 91%
## Summary

Both models achieved high accuracy, indicating strong overall performance. Model 2, trained on oversampled data, shows improved recall for the high-risk class compared to Model 1. The choice between models may depend on the specific goals. If identifying high-risk loans is crucial, Model 2 might be preferred due to its higher recall for the high-risk class. Consider the business implications: Is it more critical to correctly identify high-risk loans (even if it means more false positives), or is a balanced performance more important? The decision should be based on a balance between precision and recall, considering the business context and priorities. If a more cautious approach is needed (minimizing false negatives), Model 2 might be favored.
