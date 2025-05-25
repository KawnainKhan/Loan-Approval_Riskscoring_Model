# Final Project-Loan Approval and Riskscoring Model
Dual-target machine learning model for loan approval and risk scoring using various algorithms.
# 🧠 Loan Approval & Risk Scoring ML Pipeline

This repository contains a machine learning pipeline that jointly predicts:

1. ✅ **Loan Approval** – Binary classification (`Approved` / `Not Approved`)
2. ⚠️ **Risk Scoring** – Financial risk score (numerical or categorical)

Our primary goal is to **maximize precision**, especially for identifying high-risk or ineligible applicants with minimal false positives.

---

## 🎯 Project Goal

- Build a unified model to **simultaneously predict loan approval and applicant risk**
- Use distinct algorithms for each target, while optimizing for **precision** on the classification task

---

## ⚙️ Models Used

- **Isolation Forest** – Outlier detection for risk scoring
- **CatBoost** – Handles categorical variables well; used in both targets
- **XGBoost** – High-performance gradient boosting model
- **Logistic Regression** – Baseline classification
- **Decision Tree** – Interpretable logic-based model

Each model is evaluated independently, and the best-performing one per target is selected.

---

## 📈 Evaluation Metrics

- **Loan Approval (Classification)**  
  - **Primary focus:** Precision  
  - Other metrics: Recall, F1-Score, AUC-ROC

## 🧪 Features Used

- **Personal Info**: Age, Marital Status, Education, Employment Status
- **Financial Data**: Annual Income, Debt-to-Income Ratio, Net Worth, Savings
- **Loan Info**: Amount, Purpose, Duration, Monthly Payment
- **Credit Behavior**: Credit Score, Utilization, Payment History, Inquiries

- # Midterm Project - Amarcord Bank Outlier Detection Using Isolation Forest

This project implements an outlier detection model to identify suspicious bank transfers exceeding 500,000 units, helping Amarcord Bank flag potential high-risk transactions.

---

## 🏦 Project Overview

- **Goal:** Detect anomalous bank transfers over 500k to mitigate fraud and financial risk.
- **Bank:** Amarcord
- **Approach:** Use an Isolation Forest-based anomaly detection model to identify outliers in transaction data.
- **Contamination Rate:** 0.05 (i.e., 5% of the data is assumed to be anomalous)

---

## ⚙️ Model Details

- **Algorithm:** Isolation Forest (unsupervised outlier detection)
- **Contamination:** 5% of transactions are expected to be outliers
- **Input Features:** Synthetic dataset of bank transfers generated using Python, simulating transfer amounts and other relevant features
- **Output:** Binary flag indicating if a transaction is anomalous

---

## 🚀 How It Works

1. Generate synthetic transfer data using Python.
2. Train the Isolation Forest model on this data.
3. Predict whether new transactions are outliers based on learned patterns.
4. Transactions flagged as outliers (contamination rate 0.05) are reviewed for potential fraud or compliance issues.

---

## 📈 Evaluation

- Model performance is evaluated based on the precision of detecting true outliers.
- Balancing false positives and false negatives is crucial to avoid unnecessary investigations or missed frauds.

---






