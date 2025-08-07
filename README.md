💼 Customer Churn Prediction with Machine Learning

Predicting whether a customer will leave a telecom service (churn) is a key challenge for customer retention teams. In this project, we built a supervised machine learning model to solve this problem using real-world customer data.



📌 Problem Statement

Can we predict which customers are likely to churn based on their usage, account information, and demographics?**

This project applies machine learning to identify patterns in customer behavior and provide actionable insights to reduce churn.



 🧠 What This Project Covers

- 📊 **Exploratory Data Analysis (EDA)**
- 🧹 **Data Preprocessing & Encoding**
- ⚙️ **Feature Selection & Engineering**
- 🤖 **Model Building**
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - XGBoost
- ✅ **Model Evaluation & Comparison**



 📁 Dataset

- **Source:** Kaggle - Telco Customer Churn  
- **Rows:** 7,043 customer records  
- **Target Variable:** `Churn` (Yes/No)



## 📈 Model Results

| Model               | Accuracy Score |
|---------------------|----------------|
| **XGBoost**         | **80.3%**      |
| Random Forest       | 78.2%          |
| Logistic Regression | 76.3%          |
| Decision Tree       | 73.5%          |

✅ **XGBoost** performed the best and was selected as the final model.



 🔍 Key Insights

- **Senior citizens** and **month-to-month contract** customers show higher churn.
- **Longer tenure**, **automatic payment methods**, and **fiber optic internet** are key indicators of customer behavior.
- Feature engineering and the use of XGBoost significantly improved the model’s performance.








