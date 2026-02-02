# Customer Churn Prediction using Explainable Machine Learning

This repository includes an end-to-end machine learning project that uses **Logistic Regression** to forecast customer churn and **SHAP** to explain model decisions.

## Overview of the Project
Businesses can identify clients who are likely to discontinue using a service by employing customer churn prediction. Customers are classified as either churned or not in this research using a supervised learning approach based on billing, service usage, and demographic data.

## DatasetIBM Sample Data from the Telco Customer Churn Dataset
Kaggle is the source.
It includes account information, service data, and consumer demographics.
The target variable is called "Churn."

Using `kagglehub`, the dataset is programmatically downloaded within the notebook.
## Strategy
- Data cleansing and preprocessingScaling features and encoding categorical variables
Developing a Classifier for Logistic Regression
Assessing model performance through precision
- Interpreting predictions using SHAP values ##Outcomes
- Model accuracy: ~77..64%
Contract type, tenure, and monthly charges are the most important factors.



## How to Run
1. Clone the repository:
```bash
https://github.com/jerem-a11y/customer-churn-prediction
