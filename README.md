# 📊 Customer Churn Prediction using Machine Learning

### Predicting telecom customer churn using Python, Scikit-Learn, and XGBoost

This project builds an end-to-end **machine learning pipeline** to predict whether a customer will churn (leave a service) based on their usage and contract patterns.  
It walks through every major stage of an ML lifecycle — from **EDA** and **feature engineering** to **model comparison** and **visualization**.

---

## 🚀 Project Overview

Customer churn is one of the most critical business challenges faced by subscription-based companies.  
By predicting churn, organizations can identify at-risk customers and take proactive retention measures.  

This notebook analyzes a **telecom dataset** and compares six popular ML models:
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Random Forest  
- XGBoost  

---

## 📁 Dataset Information

**Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
**File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`  
**Rows:** 7,043  
**Features:** 21  

### Key Columns
| Feature | Description |
|----------|-------------|
| `customerID` | Unique ID for each customer |
| `tenure` | Number of months the customer has stayed |
| `Contract` | Type of contract (Month-to-month, One year, Two year) |
| `MonthlyCharges` | Monthly bill amount |
| `TotalCharges` | Total amount paid by the customer |
| `Churn` | Target variable (Yes = customer left) |

---

## 🧠 Workflow Diagram (Text Format)

```text
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering & Scaling
      ↓
Train-Test Split
      ↓
Model Training (6 Algorithms)
      ↓
Evaluation (Accuracy, Confusion Matrix, ROC-AUC)
      ↓
Visualization & Feature Importance
      ↓
Prediction on New Data
