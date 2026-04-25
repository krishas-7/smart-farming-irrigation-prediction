# 🌾 Smart Farming – Irrigation Prediction

> ML-powered binary classification model to predict whether crops need irrigation — helping farmers save water and improve yield.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=xgboost&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

---

## 📌 Project Overview

This project applies supervised machine learning to agriculture — predicting whether a given crop needs irrigation based on **soil conditions** and **weather parameters**. The system helps farmers make data-driven irrigation decisions, reducing water wastage and preventing over/under-irrigation.

---

## 🔍 Problem Statement

Farmers often rely on intuition or fixed schedules for irrigation — leading to water wastage or crop stress. This project provides a data-driven alternative by training a model on historical soil and weather data.

---

## 🤖 Models Used

| Model | Notes |
|---|---|
| Random Forest | Ensemble — handles non-linear relationships |
| XGBoost | Boosting — high accuracy on imbalanced data |

---

## 🔧 ML Workflow

```
Raw Data → Cleaning → Feature Engineering → Encoding → Class Imbalance Handling → Training → Evaluation
```

**Key technique:** Class imbalance handled via **threshold tuning** and **class weighting** — ensuring the model correctly identifies cases where irrigation IS needed (not just predicts the majority class).

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

*(5-metric evaluation ensures rigorous performance analysis beyond simple accuracy)*

---

## 📁 Features Used

- Soil moisture levels
- Soil type / composition
- Ambient temperature
- Humidity
- Rainfall history
- Crop type

---

## 🗂️ Project Structure

```
smart-farming-irrigation-prediction/
│
├── data/
│   └── farming_data.csv           # Soil & weather dataset
│
├── notebooks/
│   └── irrigation_prediction.ipynb
│
├── src/
│   ├── preprocessing.py           # Cleaning & feature engineering
│   ├── model_training.py          # RF + XGBoost training
│   └── evaluation.py              # Metrics & confusion matrix
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

```bash
git clone https://github.com/krishas-7/smart-farming-irrigation-prediction.git
cd smart-farming-irrigation-prediction
pip install -r requirements.txt
jupyter notebook notebooks/irrigation_prediction.ipynb
```

---

## 🌱 Impact

- Reduces unnecessary water usage
- Prevents crop damage from under-irrigation
- Scalable to different crop types and geographies

---

*Built by [Krisha Shah](https://www.linkedin.com/in/krishas7) · Mumbai, India*
