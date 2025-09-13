# 📊 Customer Churn Prediction

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)
![Platform: Jupyter](https://img.shields.io/badge/Platform-Jupyter-informational?logo=jupyter)
![Last Commit](https://img.shields.io/github/last-commit/Amanyadav-07/Customer-Churn-Prediction)
![Issues](https://img.shields.io/github/issues/Amanyadav-07/Customer-Churn-Prediction)

Predicting customer churn is essential for telecom companies aiming to retain valuable customers and improve business outcomes. This repository offers a comprehensive solution to predict telecom customer churn using machine learning techniques, with an emphasis on data-driven insights and model interpretability.

---

## 🚀 Project Overview

This project analyzes telecom customer data to identify factors leading to customer churn and predict which customers are likely to leave. The workflow encompasses:

- Data preprocessing & cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Addressing class imbalance with SMOTE
- Feature scaling
- Model training, evaluation, and selection

The final deliverable is a robust machine learning pipeline, with clear business recommendations based on the findings.

---

## 📂 Dataset Information

The dataset contains customer profiles, service details, account information, and a churn indicator. Key features include:

- Customer demographics (gender, age, etc.)
- Service subscription details (internet, phone, contract type)
- Billing information (monthly charges, payment methods)
- Tenure and churn status

---

## 🛠️ Tools & Libraries

- **Python** (core language)
- **pandas**, **numpy** (data manipulation)
- **scikit-learn** (ML algorithms, preprocessing, evaluation)
- **imbalanced-learn** (SMOTE for class balancing)
- **xgboost** (advanced gradient boosting)
- **matplotlib**, **seaborn** (visualizations)

---

## 📈 EDA Highlights

Key insights from Exploratory Data Analysis:

- **Short Tenure → Higher Churn:** Customers with a short tenure are more likely to churn.
- **High Monthly Charges → More Churn:** Customers paying higher monthly charges tend to leave.
- **Contract Type Matters:** Month-to-month contracts show the highest churn rates.

Visualizations and detailed analysis can be found in the [Customer_Churn_Prediction.ipynb](./Customer_Churn_Prediction.ipynb) notebook.

---

## 🤖 Model Performance

Three machine learning models were compared:

- **Logistic Regression**
  - ~76% accuracy
  - **Best recall** among all models
  - Chosen as the final model for its simplicity and interpretability
- **Random Forest**
  - ~75% accuracy
- **XGBoost**
  - ~75% accuracy

All models were evaluated using accuracy, recall, precision, and F1-score, with SMOTE applied to mitigate class imbalance.

---

## 💡 Business Insights

- **Retention Focus:** Target short-tenure and high monthly charge customers for retention programs.
- **Contract Optimization:** Consider incentivizing longer-term contracts to reduce churn.
- **Model Deployment:** The chosen Logistic Regression model offers actionable predictions, aiding business teams in proactive churn management.

---

## 🏃‍♂️ How to Run

1. **Clone the Repository**
    ```bash
    git clone https://github.com/Amanyadav-07/Customer-Churn-Prediction.git
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
    *(See the notebook for specific package versions if needed.)*

3. **Run the Notebook**
    - Open `Customer_Churn_Prediction.ipynb` in Jupyter Notebook or VS Code.
    - Execute cells sequentially to reproduce the workflow and results.

---

## 📁 File List

- **Customer_Churn_Prediction.ipynb** — Main analysis notebook
- **Customer_Churn_Prediction.pdf** — Project report (summary & visualizations)

---

## 👤 Author

- **Aman Kumar Yadav**
- 📧 amanyadav32327@gmail.com

---

> For questions, suggestions, or collaboration opportunities, feel free to open an issue or contact via email!