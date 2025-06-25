# 🏦 Retail Banking Risk Analytics Project

## 📌 Objective
Predict whether a loan is **risky or not** using historical loan data from LendingClub (2007–2018). This project helps banks proactively identify high-risk borrowers.

## 📊 Dataset
- Source: LendingClub (accepted_2007_to_2018Q4.csv)
- Size: ~2.6M records, 145 columns
- Target: `loan_status_binary` (0 = Good, 1 = Risky)

## 🔧 Steps Performed
- Data Cleaning & Handling Missing Values
- Feature Engineering (handling categorical columns, datetime)
- Label Encoding / One-Hot Encoding
- Model Training with:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Hyperparameter Tuning using `RandomizedSearchCV`
- Evaluation using Confusion Matrix, Classification Report, ROC Curve
- Model Interpretation with Feature Importance

## ✅ Final Model
- Model: **XGBoostClassifier**
- Accuracy: **99.99%**
- AUC: ~**1.0**
- Top Features: `grade`, `int_rate`, `emp_length`, `dti`, etc.

## 📁 Project Structure

