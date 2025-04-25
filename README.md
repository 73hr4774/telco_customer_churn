# 📉 Telco Customer Churn Prediction

This project focuses on predicting customer churn in a telecom company using machine learning. It helps identify which customers are likely to leave so that the business can take proactive steps to retain them.

---

## 🔍 Problem Statement

Customer churn can significantly impact telecom companies. This project aims to build a predictive model to classify customers as likely to churn or stay, based on service usage patterns, demographics, and billing information.

---

## 📊 Dataset Information

- Source: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Total Records: 7,043
- Target: `Churn` (Yes/No)
- Features:
  - `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - `tenure`, `PhoneService`, `InternetService`, etc.
  - `MonthlyCharges`, `TotalCharges`
  - `Contract`, `PaymentMethod`, etc.

---

## ⚙️ Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Modeling**: Logistic Regression, Random Forest, XGBoost
- **Deployment**: Streamlit

---

## 🚀 How to Run Locally

1. Clone the repository  
```bash
git clone https://github.com/73hr4774/telco_customer_churn.git
cd telco_customer_churn

pip install -r requirements.txt

streamlit run app.py

🌐 Deployed App
👉 Click here to view the deployed Streamlit app
https://telcocustomerchurn-app.streamlit.app/

🧠 Key Insights
Customers with shorter tenure and month-to-month contracts are more likely to churn.

Fiber optic users showed higher churn rates compared to DSL users.

Electronic check payments were associated with higher churn.
