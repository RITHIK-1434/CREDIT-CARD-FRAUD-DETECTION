# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Due to the extreme class imbalance in the dataset, we applied SMOTE (Synthetic Minority Oversampling) to balance the classes and improve the performance of our classifiers.

---

## 📊 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Total Records:** 284,807
- **Fraudulent Transactions:** 492 (≈0.17%)

---

## 🧪 Techniques & Tools

- **Data Preprocessing**
- **Handling Imbalanced Data:** SMOTE
- **Modeling:** Logistic Regression, Random Forest, XGBoost
- **Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 🔍 Model Performance (Example Results)

| Model              | Accuracy | Recall (Fraud) | Precision |
|-------------------|----------|----------------|-----------|
| Logistic Regression | 99.2%   | 84%            | 93%       |
| Random Forest       | 99.5%   | 90%            | 96%       |
| XGBoost             | 99.6%   | **94%**        | 97%       |

✅ **Best Performing Model:** XGBoost (highest recall on fraudulent cases)

---

## 📁 Project Structure

