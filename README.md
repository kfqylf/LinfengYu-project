# Hypoxemia Prediction Using Machine Learning

This project builds classification models to predict patients at risk of hypoxemia based on non-invasive medical data such as pulse oximeter readings and lab test results.

## 🧠 Objectives
- Predict the need for blood gas analysis (BGA) using machine learning
- Reduce unnecessary manual testing and improve early detection

## 📊 Dataset
- Medical test results with features including pH value, pO2, pCO2, etc.
- Binary target: requires BGA (yes/no)

## 🔧 Methods
- Data preprocessing: MinMaxScaler, PCA, SMOTE
- Models: Logistic Regression, KNN, SVM, Random Forest, XGBoost, LightGBM, CatBoost
- Evaluation: F1-score, recall, precision

## ✅ Key Results
- High recall achieved with XGBoost and LightGBM
- pH value and oxygen saturation identified as important features

## 📁 Files
- `hypoxemia_model.ipynb`: full modeling notebook
- `data/`: contains cleaned dataset (if shareable)
- `README.md`: this file

## 📌 Skills Applied
`Python`, `scikit-learn`, `XGBoost`, `EDA`, `Medical Data`, `SMOTE`, `PCA`, `Model Evaluation`
