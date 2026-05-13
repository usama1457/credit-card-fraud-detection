# 💳 Credit Card Fraud Detection

## 📌 Overview

Built a machine learning classification model to detect fraudulent credit card transactions using Logistic Regression. The project focuses on handling highly imbalanced financial transaction data and predicting whether a transaction is legitimate or fraudulent.

---

## 📊 Dataset

* Dataset: Credit Card Fraud Detection Dataset
* Contains anonymized transaction features (`V1` to `V28`), transaction amount, and transaction class.
* Target Variable:

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction
* The dataset is highly imbalanced, with very few fraud cases compared to normal transactions.

---

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 🔍 Workflow

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Handling imbalanced data using under-sampling
* Train-test split
* Logistic Regression model training
* Model evaluation using accuracy score
* Fraud transaction prediction system

---

## 📈 Evaluation

The model was evaluated using:

* Training Accuracy
* Test Accuracy

---

## 🔮 Prediction System

The trained model predicts whether a new credit card transaction is:

* Legitimate
* Fraudulent

---

## 🚀 Future Improvements

* SMOTE oversampling
* Precision, Recall & F1-score evaluation
* ROC-AUC analysis
* Model comparison using Random Forest and XGBoost
* Streamlit deployment for real-time interaction

