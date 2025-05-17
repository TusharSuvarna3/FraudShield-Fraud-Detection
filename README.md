# FraudShield - Fraud Detection System
FraudShield is a machine learning project designed to identify fraudulent financial transactions using behavioral and transactional data. It evaluates multiple classification models on a highly imbalanced dataset and highlights both statistical performance and real-world relevance.

---

## 🧠 Overview
- Developed fraud detection models using Random Forest, XGBoost, Gradient Boosting, SVM, and Logistic Regression
- Addressed class imbalance using SMOTE
- Applied feature engineering, model evaluation, and performance tuning

---

## 🔧 Tools & Technologies
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn, Seaborn, Matplotlib  
- **Techniques**: SMOTE, Feature Importance, Precision-Recall Analysis

---

## 📊 Model Performance Summary

| Metric               | Random Forest | XGBoost | Gradient Boosting |
|----------------------|---------------|---------|--------------------|
| Accuracy             | ✅ High        | ✅ High | Moderate           |
| Precision (Fraud)    | **Highest**   | High    | Moderate           |
| Recall (Fraud)       | Moderate      | Moderate| **Highest**        |
| AUC                  | 0.86          | 0.90    | **0.95**           |
| AUC-PR               | **Highest**   | High    | Moderate           |

---

## 📌 Feature Importance

The most impactful features in detecting fraud were:

1. **Transaction Amount** – Strongest predictor of fraud
2. **Temporal Features** – Time of day, day of week, and month revealed fraud-prone periods
3. **User Age** – Age patterns influenced the likelihood of fraud
4. **Transaction Category** – Categories like *food/dining*, *personal care*, and *grocery* had significant fraud patterns
