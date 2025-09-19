# APR_Ass01 – Credit Card Fraud Detection

## 📌 Introduction
This project focuses on detecting **fraudulent credit card transactions** using machine learning.  
The dataset is highly **imbalanced** (frauds ≈ 0.17%, non-frauds ≈ 99.83%).  
We explore data preprocessing, resampling techniques, and different classifiers to handle this imbalance.

---

## 🎯 Goals
- Understand the dataset distribution.  
- Handle **imbalanced data** using **NearMiss undersampling** and **SMOTE oversampling**.  
- Train and evaluate multiple classifiers:
  - Logistic Regression
- Compare results using accuracy, precision, recall, F1-score, and ROC-AUC.  
- Visualize learning curves, confusion matrices, and ROC curves.  

---

## 📊 Dataset
- **Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Features**: 30 anonymized features (`V1…V28`, `Time`, `Amount`)  
- **Target**:  
  - `0` → Non-fraud  
  - `1` → Fraud  

---

## 📈 Results
- Logistic Regression with tuned parameters gave **~94–96% accuracy** and ROC-AUC ≈ **0.97**.   
- ROC Curve and Confusion Matrix confirm that **recall is crucial** (better to detect frauds even if some false positives occur).  

---

## 📂 Project Structure
