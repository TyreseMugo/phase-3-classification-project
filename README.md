# Phase 3 Classification Project: Telecom Customer Churn Prediction

## Overview
This project aims to predict customer churn for a telecom company using machine learning. The goal is to help the company reduce customer loss and optimize marketing campaigns.

Dataset used: [Kaggle Telecom Churn Dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)

## Business Understanding
**Stakeholder:** Telecom company  
**Problem:** Predict which customers are likely to churn (leave the service).  
**Importance:** Helps the business retain customers and improve revenue.

## Data Understanding
The dataset contains 3,333 customer records with 21 features, including:

- Customer demographics (`state`, `area code`, etc.)
- Service usage (`total day minutes`, `total eve minutes`, etc.)
- Account details (`international plan`, `voice mail plan`, etc.)
- Customer behavior (`customer service calls`)
- Target variable: `churn` (Yes/No)

## Modeling
- Baseline model: Logistic Regression
- Nonparametric model: Decision Tree
- Hyperparameter tuning was applied to improve model performance.
- Preprocessing included encoding categorical features and handling non-numeric columns.

## Evaluation
- Metrics used: Accuracy, Precision, Recall, F1-score
- Train-test split: 75%-25%, stratified by target variable

## Conclusion
- Feature importance analysis shows `customer service calls` and `international plan` are strong predictors.
- The predictive models can be used by the telecom company to identify high-risk churn customers and take proactive actions.

## Files in Repository
- `data/` – CSV dataset
- `notebooks/` – Jupyter Notebook with analysis
- `presentation/` – PDF slides for non-technical stakeholders
