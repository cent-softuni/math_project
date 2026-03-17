# Personal Loan Prediction – ML Project

## Overview
This project focuses on predicting whether a bank customer will accept a personal loan offer. The goal is to help the marketing team target the right customers and improve conversion rates.

The dataset comes from AllLife Bank and contains customer demographic and financial information.

## Business Problem
AllLife Bank wants to increase the number of customers taking personal loans. Currently, only a small percentage of liability customers convert to loan customers.

Objective:
- Identify customers with high probability of accepting a loan
- Improve marketing efficiency
- Increase conversion rate


## Dataset
The dataset includes the following key features:

- Age, Experience
- Income
- Family size
- Credit card spending (CCAvg)
- Education level
- Mortgage
- Online usage
- CD Account / Securities Account
- Target variable: `Personal_Loan` (0 / 1)


## Approach

### 1. Data Preprocessing
- Checked for missing values and inconsistencies
- Removed irrelevant columns (e.g. ID, ZIP Code)
- Feature scaling applied where needed

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of key variables
- Correlation analysis
- Target-wise feature comparison

### 3. Model Building
Multiple models were tested:

- Logistic Regression
- Decision Tree
- Random Forest

### 4. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision / Recall
- Confusion Matrix
- ROC-AUC (if applied)


## Key Results

- Customers with **higher income and credit card spending** are more likely to accept loans
- **CD Account holders** show strong correlation with loan acceptance
- Tree-based models (Random Forest) performed best


## Business Insights

- Focus marketing campaigns on:
  - High-income customers
  - Customers with CD accounts
  - Active digital banking users

- Reduce targeting cost by avoiding low-probability segments


## Tech Stack

- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn


## Project Structure

├── AIML_ML_Project_full_code_notebook.ipynb
├── Loan_Modelling.csv
├── README.md