# Customer Churn Prediction

This project builds a customer churn prediction model using **Logistic Regression** and **SHAP** for model interpretability.

## Dataset
- **Telco Customer Churn Dataset (IBM)**
- Source: [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Downloaded programmatically using `kagglehub` in the notebook
- Target variable: `Churn` (Yes / No)

## Methodology
- Data preprocessing (missing values, encoding, scaling)
- Logistic Regression model training and evaluation
- Model interpretability with SHAP

## Results
- Accuracy: ~77.64%
- Key churn drivers identified: contract type, tenure, monthly charges

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/jerem-a11y/customer-churn-prediction.git
