# customer-churn-detection
Machine Learning project to predict customer churn using XGBoost with 85% accuracy.
# 🏦 Customer Churn Detection

## 📌 Overview
This project predicts whether a bank customer will **churn** (leave the bank) or **stay** using machine learning.  
Customer churn prediction helps banks identify customers who are likely to leave, so they can take proactive actions (offers, support, retention strategies).

---

## 📊 Dataset
- Source: Kaggle Bank Customer Churn Dataset
- Total Customers: **10,000**
- Features: **12** (e.g., credit score, country, gender, age, balance, products, etc.)
- Target Variable:  
  - `0` → Customer stayed  
  - `1` → Customer churned (left)  

---

## ⚙️ Steps & Methodology
1. **Data Preprocessing**
   - Encoded categorical variables (`country`, `gender`)
   - Scaled numerical features
   - Handled **class imbalance** using **SMOTE**

2. **Model Training**
   - Tested multiple models: Logistic Regression, Random Forest, XGBoost
   - Final choice: **XGBoost Classifier**

3. **Why XGBoost?**
   - Handles imbalanced data better
   - Provides feature importance
   - Achieves higher accuracy and ROC-AUC on tabular data

---

## 📈 Results
- **Accuracy:** ~85%
- **ROC-AUC:** ~0.83
- **Precision/Recall for churners improved** after SMOTE balancing

---

## 🔑 Key Insights
- Age, balance, and credit score are strong churn indicators
- Active members are less likely to churn
- High tenure customers have better retention

---


