# Loan-Approval_Riskscoring_Model
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



