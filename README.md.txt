# 📉 Customer Churn Prediction & Retention Intelligence System

## 🚀 Project Overview

Customer churn is one of the most critical challenges in subscription-based businesses such as telecom, banking, and SaaS companies. Losing customers directly impacts revenue and long-term business growth.

This project applies machine learning to:
- Predict whether a customer will churn
- Identify key drivers of customer churn
- Provide actionable retention strategies to improve customer loyalty

Rather than only building a predictive model, this project focuses on **business interpretation and decision-making insights**, making it suitable for real-world deployment.

---

## 🎯 Project Objectives

The main goals of this project are:

- To analyze customer behavior and identify churn patterns
- To build a machine learning model that predicts churn
- To evaluate model performance using classification metrics
- To extract insights that can guide business retention strategies

---

## 📊 Dataset Description

The dataset used is the **IBM Telco Customer Churn dataset**, which contains information about:
- Customer demographics
- Subscription details
- Service usage
- Billing information
- Contract type

### Target Variable:
- `Churn` (Yes / No) → whether a customer left the company

---

## 🧹 Data Preprocessing Steps

To prepare the data for modeling, the following steps were performed:

### 1. Handling Missing Values
- Converted `TotalCharges` from object to numeric
- Removed missing values after conversion

### 2. Encoding Categorical Variables
- Applied one-hot encoding using `pd.get_dummies()`
- Converted categorical variables into numerical format

### 3. Feature Scaling
- Standardized numerical features using `StandardScaler`
- Ensured Logistic Regression performs efficiently

---

## 🔍 Exploratory Data Analysis (EDA)

Key insights discovered:

- Approximately **26% of customers churned**, indicating a significant retention challenge
- Customers on **month-to-month contracts** showed the highest churn rate
- Customers with **higher monthly charges** were more likely to churn
- Customers on **long-term contracts (1–2 years)** had significantly lower churn rates
- Service type and pricing structure strongly influence customer retention

---

## 🤖 Machine Learning Model

### Model Used:
- Logistic Regression

### Workflow:
1. Data splitting (80% training, 20% testing)
2. Feature scaling using StandardScaler
3. Model training on processed data
4. Prediction on unseen test data

---

## 📈 Model Evaluation

### Performance Metrics:
- Accuracy: **79%**
- Confusion Matrix used for classification performance
- Precision, Recall, and F1-score analyzed

### Key Insight:
The model performs well in predicting customer churn and can be used as a baseline model for business decision-making.

---

## 📊 Feature Importance Analysis

The model revealed that the most influential factors affecting churn include:

- Contract type (month-to-month customers are more likely to churn)
- Monthly charges (higher charges increase churn probability)
- Internet service type
- Tenure duration

These features help explain **why customers leave**, not just whether they will leave.

---

## 💡 Business Recommendations

Based on model insights:

### 1. Encourage Long-Term Contracts
Offer discounts and incentives to convert customers from monthly to yearly contracts.

### 2. Target High-Risk Customers
Identify customers with high monthly charges and offer personalized retention offers.

### 3. Improve Service Quality
Focus on improving internet service experience, especially for high-churn segments.

### 4. Bundle Services
Encourage customers to subscribe to multiple services to increase engagement and retention.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas & NumPy (Data Processing)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine Learning)

---

## 📌 Key Learnings

- End-to-end machine learning workflow
- Data cleaning and preprocessing techniques
- Handling categorical variables and missing data
- Model evaluation using classification metrics
- Translating technical results into business insights

---

## 🚀 Future Improvements

- Implement advanced models (Random Forest, XGBoost)
- Perform hyperparameter tuning for better accuracy
- Deploy model using Streamlit or Flask
- Build interactive dashboard for business users

---

## 📎 Project Link

🔗https://github.com/Ayoifemi/customer-churn-project

---

## 👩‍💻 Author

Ayomide Ifeoluwa is a Data Analyst passionate about leveraging data, machine learning, and analytics to solve real-world business problems and improve decision-making in organizations.

---

## 📢 Let's Connect

If you found this project interesting, feel free to connect or reach out!

---
