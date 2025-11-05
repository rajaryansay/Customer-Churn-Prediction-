# 📊 Telco Customer Churn Analysis & Prediction

## 🧠 Project Overview
This project focuses on analyzing customer churn behavior for a telecom company using the **Telco Customer Churn Dataset**.  
Through **Exploratory Data Analysis (EDA)** and **Machine Learning modeling**, the goal is to identify key factors contributing to churn and predict whether a customer is likely to leave.

---

## 🎯 Objectives
- Understand churn patterns using statistical and visual analysis.  
- Preprocess and clean the dataset for model readiness.  
- Build and evaluate multiple ML models to predict churn accurately.  
- Identify business insights that can help reduce customer churn.

---

## 📂 Dataset
**Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
**Rows:** ~7,043  
**Columns:** 21  

### Key Features
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- `tenure`, `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`  
- **Target Variable:** `Churn` (Yes / No)

---

## 🧹 Data Preprocessing
- Converted `TotalCharges` to numeric and handled missing values.  
- Encoded categorical variables using **Label Encoding**.  
- Applied **Feature Scaling** to normalize numerical variables.  
- Balanced data using **SMOTE** (Synthetic Minority Oversampling Technique).  

---

## 📈 Exploratory Data Analysis (EDA)
Performed detailed visual and statistical exploration to identify patterns:
- **Tenure vs. Churn:** Short-tenure customers have higher churn probability.  
- **Contract Type:** Month-to-month contracts show the highest churn rate.  
- **Payment Method:** Electronic check users are more likely to churn.  
- Visualized distributions and correlations using **Matplotlib** and **Seaborn**.

---

## 🤖 Model Building
### Algorithms Used
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  

### Evaluation Metrics
| Metric | Score |
|--------|--------|
| **Accuracy** | **92%** |
| **Precision** | High |
| **Recall** | High |
| **F1-Score** | High |

> Accuracy: 92%, and strong recall, precision & F1-score for the churned (minority) class.

---

## 🧩 Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **ML Techniques:** SMOTE, Label Encoding, Feature Scaling, Model Evaluation Metrics  

---

## 📊 Results & Insights
- Achieved **92% accuracy** on churn prediction.  
- Discovered that **contract length, payment method, and tenure** are the strongest churn predictors.  
- Delivered a reproducible **EDA and Model Building pipeline** for business decision-making.  

---

## 📁 Project Structure
