# 🧠 Customer Churn Prediction System

A **Machine Learning-based Web Application** built with **Streamlit** that predicts whether a customer is likely to **churn (leave)** based on their service usage patterns, contract type, and other key features. The system empowers businesses to identify high-risk customers and take proactive retention measures.

---

## 🔍 Overview

This project aims to solve the problem of customer retention by predicting churn using historical data. A logistic regression model is trained on a cleaned Telco Customer dataset and deployed using Streamlit to provide an interactive UI for real-time predictions.

---

## ✨ Features

✅ Predict customer churn based on input features
✅ Interactive form built with **Streamlit**
✅ Preprocessed, cleaned, and encoded customer dataset
✅ Logistic Regression model with **85.6% accuracy**
✅ Encodes categorical features and scales numerical features automatically
✅ Instant predictions for any customer profile

---

## 🧪 Model Pipeline

* 🔹 Dataset: Telco Customer Churn dataset (7,000+ rows)
* 🔹 Data Cleaning: Removed irrelevant columns, handled nulls, and converted datatypes
* 🔹 Encoding: Categorical features encoded using `LabelEncoder`
* 🔹 Scaling: Applied `StandardScaler` to numeric fields
* 🔹 Model: Logistic Regression from `scikit-learn`
* 🔹 Evaluation: Accuracy \~85.57%

---

## 📊 Input Fields

* Gender
* Senior Citizen status
* Partner & Dependents
* Tenure
* Phone Service
* Multiple Lines
* Contract Type
* Total Charges

---

## 🖥️ Tech Stack

| Tool          | Purpose                       |
| ------------- | ----------------------------- |
| Python        | Backend development           |
| Pandas, NumPy | Data manipulation and math    |
| Scikit-learn  | Model building and evaluation |
| Streamlit     | Web app interface             |
| Pickle        | Model serialization           |

---

## ✅ Accuracy

```
Logistic Regression:
Accuracy: 85.57%
```
