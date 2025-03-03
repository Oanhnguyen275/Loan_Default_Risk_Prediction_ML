
## Overview of the Analysis

This analysis focuses on evaluating machine learning models for credit risk classification. The goal is to determine whether a loan applicant is a low-risk or high-risk borrower based on financial data.

## Purpose of the Analysis

The purpose of this analysis is to compare different machine learning models to assess their accuracy, precision, and recall in predicting credit risk. By evaluating these models, we can determine which is the most reliable for predicting high-risk loan applicants.

## Financial Data and Prediction Target
The dataset contains financial information on loan applicants, including:

Loan Size: The amount of the loan applied for.

Interest Rate: The percentage of interest charged on the loan.

Borrower Income: The applicant’s annual income.

Debt-to-Income Ratio: The ratio of total debt to income.

Number of Accounts: The number of financial accounts the borrower has.

Derogatory Marks: Negative marks on the borrower’s credit history.

Total Debt: The total amount of outstanding debt.


## Stages of the machine learning process:
Data Preprocessing: Cleaned and transformed data, handled missing values, and performed feature encoding.

Feature Engineering: Selected relevant features to improve model performance.

Model Selection: Tested multiple models, including Logistic Regression and other classification algorithms.

Training and Testing: Split data into training and testing sets to evaluate model performance.

Evaluation: Used accuracy, precision, and recall metrics to compare models.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Confusion Matrix:

[[14924    77]
 [   31   476]]

Interpretation:

14,924 correctly predicted low-risk loans (0).

77 incorrectly predicted low-risk loans (0) when they were actually high-risk (1).

31 incorrectly predicted high-risk loans (1) when they were actually low-risk (0).

476 correctly predicted high-risk loans (1).

## Summary

Performance Considerations:

If predicting high-risk loans (1s) correctly is the priority (minimizing false negatives), a model with high recall should be chosen.

If minimizing false positives (incorrectly classifying a low-risk loan as high-risk) is crucial, a model with high precision is preferred.

Best Performing Model: The model with the highest accuracy, precision, and recall should be considered the best-performing model. If recall is prioritized (to reduce false negatives), then a model with high recall for 1 predictions is preferred.
