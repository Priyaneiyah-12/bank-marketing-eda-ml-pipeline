# 📊 Customer Subscription Prediction using Bank Marketing Data

## 📌 Project Overview
This project focuses on predicting whether a customer will subscribe to a term deposit based on marketing campaign data from a Portuguese bank.

The solution includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling Class Imbalance
- Machine Learning Pipeline
- Model Evaluation & Optimization

---

## 🎯 Business Objective
The goal is to help banks:
- Improve marketing campaign efficiency
- Target high-probability customers
- Reduce operational costs of telemarketing

---

## 📂 Dataset
- Source: UCI Bank Marketing Dataset
- Records: ~45,000 customers
- Target Variable: `y` (Yes/No subscription)

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights:
- Dataset is highly imbalanced (~11% positive class)
- Call duration strongly impacts conversion
- Previous campaign outcome influences success
- Seasonal trends affect subscription rates

---

## 🛠️ Feature Engineering
- Created new features:
  - `campaign_success`
  - `recent_contact`
  - `age_group`
  - `duration_age_ratio`

- Applied:
  - One-Hot Encoding
  - Standard Scaling
  - Quantile Binning

---

## 🤖 Machine Learning Model
Model used:
- Random Forest Classifier

Handling imbalance:
- Class Weight Balancing
- SMOTE (Synthetic Oversampling)

---

## 📊 Model Evaluation
Metrics used:
- Macro F1 Score
- ROC-AUC Score
- Confusion Matrix

Results:
- ROC-AUC: ~0.91+
- Improved minority class prediction using SMOTE

---

## 📈 Key Insights
- Targeted calling increases ROI significantly
- Removing call duration makes model realistic for pre-call prediction
- Feature importance highlights customer behavior patterns

---

## 🚀 Business Recommendations
- Focus on high-probability segments
- Optimize campaign timing (month/season)
- Use model as decision-support tool
- Continuously retrain with new data


