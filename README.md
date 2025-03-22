# 📊 Telco Customer Churn Prediction

This project predicts customer churn using machine learning models (Random Forest and XGBoost) and explains model decisions using SHAP values. It is based on the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn).

## 📁 Dataset
- Source: Kaggle - [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- Rows: ~7,000
- Target: `Churn` (Yes/No)

## 🧠 Models Used
- Random Forest Classifier
- XGBoost Classifier

## 📈 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 🔍 Explainability
SHAP (SHapley Additive exPlanations) is used to interpret the XGBoost model and identify top drivers of churn.

## 💡 Key Insights
- Long tenure customers are less likely to churn
- Month-to-month contracts are highly predictive of churn
- SHAP plots reveal that contract type and monthly charges have the most impact
