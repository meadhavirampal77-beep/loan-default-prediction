# Loan Default Risk Prediction using Machine Learning

## Project Overview

This project predicts whether a customer is likely to default on a loan using machine learning techniques. The objective is to support risk-aware lending decisions by identifying customers with a higher probability of loan default.
## Business Problem

Financial institutions face significant losses when borrowers fail to repay loans. This project develops a predictive model using customer financial and behavioural features to estimate loan default risk before loan approval.

## Dataset

**Dataset:** Solar Panel Financing Loan Dataset

**Target Variable:** Defaulted

**Features Used:**
- Income
- Loan Amount
- Credit Score
- Past Payments On Time
  
## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Project Workflow

- Data Loading
- Data Exploration
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Feature Engineering
- Train-Test Split
- Logistic Regression Model
- Model Evaluation
- Business Interpretation

## Exploratory Data Analysis

The analysis highlighted several important observations:

- Customers with lower credit scores showed a higher probability of loan default.
- Lower income was associated with increased default risk.
- Correlation analysis helped understand relationships between the financial variables before model development.

## Feature Engineering

A new feature called "Loan-to-Income Ratio" was created:

Loan_to_Income = Loan_Amount / Income

This feature improves the model by representing the customer's repayment burden.

## Machine Learning Model

The project uses:

- Logistic Regression

---

## Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- Classification Report

---

## Business Outcome

The analysis indicates that customers with:

- Lower credit scores
- Poor repayment history
- Higher Loan-to-Income ratios

are more likely to default on loans.

The model can support financial institutions in improving lending decisions and reducing financial risk.

---

## Repository Contents

- `Loan_Default_Prediction.ipynb` – Complete notebook
- `solar_panel_loan_data.csv` – Dataset
- `README.md` – Project documentation

---

## Future Improvements

- Train additional machine learning models for comparison.
- Perform hyperparameter tuning.
- Use a larger real-world dataset.
- Deploy the model using Flask or FastAPI.

---

## Author

**Meadhavi Rampal**

M.Sc. Data Science & Analytics

Berlin, Germany

---
This project was developed as part of my M.Sc. in Data Science & Analytics to demonstrate practical machine learning techniques for predictive risk modelling in financial services.
