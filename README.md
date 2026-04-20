# Customer Churn Prediction

This project predicts whether telecom customers are likely to leave the company.

## Goal
Help the business identify high-risk customers and reduce churn.

## What I did
- Merged multiple datasets (contract, personal, internet, phone)
- Performed exploratory data analysis (EDA)
- Engineered features such as tenure and total charges
- Trained multiple models (Logistic Regression, Random Forest, CatBoost)
- Evaluated performance using AUC-ROC

## Results
- Best model: CatBoost
- AUC-ROC: ~0.90
- Model successfully identifies customers at risk of churn

## Key Insights
- Month-to-month contracts have the highest churn
- Higher monthly charges increase churn risk
- Customers without tech support are more likely to leave

## Tools
Python, Pandas, Scikit-learn, CatBoost

## Business Impact
This model can help the company identify customers at risk of leaving and take proactive steps such as offering discounts or improving service, reducing churn and protecting revenue.
