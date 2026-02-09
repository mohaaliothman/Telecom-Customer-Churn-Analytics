# Telco-Churn-Prediction-Feature-Engineering

End-to-end customer churn analytics and prediction project using the Telco Customer Churn dataset. The work covers data cleaning, exploratory analysis, feature engineering, outlier detection, and multiple predictive models (ML + DL).

## Dataset
- **Telco Customer Churn** (Kaggle): `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Target: **Churn** (binary)

## What This Project Does
### 1) Data Cleaning & Preparation
- Convert `TotalCharges` to numeric and handle missing values
- Check duplicates and basic dataset profiling
- Encode categorical variables using one-hot encoding / numeric mapping

### 2) Exploratory Data Analysis (EDA)
- Distribution plots, scatter plots, correlation analysis
- Normality checks (Shapiro / KS tests)

### 3) Outlier / Anomaly Detection
- K-distance + KneeLocator for DBSCAN parameter intuition
- DBSCAN and Isolation Forest for anomaly detection on selected numeric features

### 4) Feature Engineering
Created additional features such as:
- `num_services`
- `charges_ratio`
- `Customer_score`
- `Tech_savvy`
- `LoyaltyScore`
- `HighValueCustomer`
- Interaction features (e.g., loyalty * tech)

### 5) Modeling & Evaluation
Models trained and evaluated using:
- Logistic Regression (baseline + engineered feature sets)
- Random Forest with GridSearchCV
- Neural Network (Keras) for churn prediction
Evaluation includes:
- Accuracy
- Confusion matrix
- Classification report (Precision/Recall/F1)

## Report
A business-focused churn report is included: `BUSINESS_ANALYTICS.pdf` (insights + recommendations).

## Author :
**Mohammad Ali Othman**
