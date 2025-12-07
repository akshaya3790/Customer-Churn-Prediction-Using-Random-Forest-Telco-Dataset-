# Customer Churn Prediction using Machine Learning #

# 📌 Business Problem
Customer churn directly impacts recurring revenue in subscription-based telecom businesses.
Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project focuses on predicting whether a customer is likely to churn, enabling businesses to take proactive retention actions such as personalized offers and support.

# 🎯 Project Objective

* Build a robust machine learning model to predict customer churn
* Identify key factors driving customer churn
* Provide data-driven insights for customer retention strategies

# ✅ Project Outcome

* Developed a churn prediction system with high ROC-AUC score
* Identified critical churn drivers such as contract type, tenure, and monthly charges
* Enabled targeted retention strategies for high-risk customers
* Prepared a production-ready model suitable for deployment

# 📊 Dataset

* Source: Telco Customer Churn Dataset
* Records: 7,000+ customers
* Target Variable: Churn (Yes / No)

# Key Features

1)Customer demographics (gender, senior citizen, dependents)
2)Subscription services (internet type, streaming services, contracts)
3)Account information (tenure, monthly charges, total charges)

# 🛠️ Technologies & Tools Used

# Programming Language
   Python

# Libraries:
   * Pandas, NumPy – Data manipulation
   * Matplotlib, Seaborn – Data visualization
   * Scikit-learn – Machine learning & evaluation
   * Joblib – Model serialization

# Project Workflow

## 1)Data Loading & Cleaning
  * Removed identifier columns
  * Handled missing values
  * Converted categorical features into numeric format
## 2)Exploratory Data Analysis (EDA)
  * Analyzed churn distribution
  * Explored churn relationships with tenure and billing patterns
## 3)Feature Engineering
  * One-hot encoding for categorical variables
  * Feature scaling using StandardScaler
## 4)Handling Class Imbalance
  * Applied class weighting to address churn imbalanc
## 5)Model Building
  * Baseline model: Logistic Regression
  * Advanced model: Random Forest Classifier
## 6)Model Evaluation
  * Accuracy
  * Confusion Matrix
  * Classification Report
  * ROC-AUC Score
  * Cross-validation for robustness
## 7)Hyperparameter Tuning
  * GridSearchCV to optimize Random Forest performance
## 8)Explainability
  * Feature importance analysis to identify churn drivers
## 9)Model Deployment Readiness
  * Saved final trained model using Joblib
