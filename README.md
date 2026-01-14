# 📉 Telecom Customer Churn Prediction

## 📌 Project Overview
The telecommunications industry faces high customer churn rates (customers switching to competitors). This project analyzes customer behavior and builds a Machine Learning model to predict which customers are at risk of leaving.

The goal is to provide actionable insights for retention strategies, focusing on maximizing **Recall** to capture as many at-risk customers as possible.

## 📊 Key Results
* **Model Accuracy:** 76%
* **Recall (Churn Class):** 82% (Significant improvement using SMOTE)
* **Business Impact:** The model successfully identified **82%** of churners, allowing the business to intervene with retention offers before the customer leaves.

## 🛠️ Tech Stack
* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression)
* **Data Handling:** SMOTE (Synthetic Minority Over-sampling Technique) for handling class imbalance.

## 🔍 Key Insights from Analysis
1.  **Contract Type:** Customers with "Month-to-month" contracts are **most likely to churn**.
2.  **Payment Method:** "Electronic Check" users have a significantly higher churn rate.
3.  **Fiber Optic:** Surprisingly, customers with Fiber Optic internet churn more than DSL users (indicating potential service quality issues).

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
