# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn prediction is an important problem in the telecom industry. Retaining existing customers is more cost-effective than acquiring new ones.

This project predicts whether a customer will leave (churn) or stay based on demographic information, service usage, contract type, and billing details.

The final model focuses on improving churn recall to reduce missed churn customers and support better retention strategies.

---

## Dataset Information

- Telecom Customer Dataset  
- Total Records: 7043  
- Total Features: 21  
- Target Variable: Churn (Yes / No)

Features include customer demographics, service details, contract information, billing details, MonthlyCharges, and TotalCharges.

---

## Project Workflow

1. Data cleaning and type conversion  
2. Handling missing values  
3. Dropping irrelevant columns (customerID)  
4. Encoding target variable (Churn)  
5. One-hot encoding categorical features  
6. Train-test split with stratification  
7. Feature scaling (for Logistic Regression)  
8. Model training and evaluation  
9. Handling class imbalance using class weights  

---

## Models Used

Logistic Regression (Baseline)  
Weighted Logistic Regression (Final Model)  
Random Forest (Comparison Model)

---

## Final Model Performance

Accuracy: ~76%  
Churn Recall: Improved from 57% to 72%  
ROC-AUC Score: ~0.84  

The weighted Logistic Regression model was selected because it improved churn recall and reduced false negatives, which is critical for business retention strategies.

---

## Tech Stack

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  
Jupyter Notebook  

---

## Project Structure

Customer-Churn-Prediction/
│
├── data/
├── notebooks/
├── requirements.txt
└── README.md

---

## Author

Mohammed Ansar  
Computer Science Graduate

