# Loan Risk Prediction – Supervised Machine Learning

## Overview

**Loan_risk_ML** is a machine learning project aimed at predicting the risk level of loan applicants. By analyzing financial data, the project classifies applicants as either low-risk or high-risk borrowers. This classification assists financial institutions in making informed lending decisions, thereby mitigating potential defaults.

## ⚙️ Project Highlights

- **Objective**: Predict the likelihood of loan default by classifying applicants into low-risk or high-risk categories.
- **Dataset**: Utilizes a synthetic dataset containing financial information of loan applicants.
- **Machine Learning Models**:
  - **Logistic Regression**: A baseline model for binary classification.
  - **Random Forest Classifier**: An ensemble method that improves prediction accuracy.
- **Evaluation Metrics**:
  - **Accuracy**: Measures the overall correctness of the model.
  - **Precision**: Indicates the accuracy of positive predictions.
  - **Recall**: Shows the ability of the model to capture all positive instances.
  - **F1-Score**: The harmonic mean of precision and recall, providing a balance between the two.
---

## 📂 Repository Structure

- `credit_risk_classification.ipynb`: Jupyter notebook containing the complete analysis, including data preprocessing, model development, training, and evaluation.
- `lending_data.csv`: The dataset used for training and testing the models.
- `Report.md`: A detailed report summarizing the methodology, results, and conclusions.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🎯 Outcome

The project successfully demonstrates the application of machine learning techniques to predict loan default risk. The Random Forest Classifier outperformed the Logistic Regression model, achieving higher accuracy and F1-score, indicating its effectiveness in identifying high-risk loan applicants.

Confusion Matrix:

[[14924    77]
 [   31   476]]

Interpretation:

14,924 correctly predicted low-risk loans (0).

77 incorrectly predicted low-risk loans (0) when they were actually high-risk (1).

31 incorrectly predicted high-risk loans (1) when they were actually low-risk (0).

476 correctly predicted high-risk loans (1).
