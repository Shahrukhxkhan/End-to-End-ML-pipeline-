# End-to-End-ML-pipeline-

Telco Customer Churn Prediction - ML Pipeline
Project Overview
This project implements a complete machine learning pipeline to predict customer churn for a telecommunications company. The solution handles data preprocessing, model training, evaluation, and deployment preparation.

Key Features
Comprehensive data preprocessing pipeline

Multiple machine learning models (Logistic Regression and Random Forest)

Hyperparameter tuning with cross-validation

Production-ready pipeline serialization

Detailed performance evaluation

Dataset Information
The Telco Customer Churn dataset contains customer information including:

Account details (tenure, contract type)

Demographic information

Service subscriptions

Billing information

Churn status (target variable)

Methodology
Data Preparation
Removed non-predictive columns

Handled missing values

Converted categorical variables

Standardized numeric features

Encoded the target variable

Machine Learning Approach
Data Preprocessing Pipeline:

Automated handling of numeric and categorical features

Built-in feature scaling and encoding

Model Training:

Logistic Regression with regularization

Random Forest with various configurations

5-fold cross-validation

Model Selection:

Grid search for optimal parameters

Accuracy-based evaluation

Complete pipeline serialization

Results
Model Performance
Model	Cross-Validation Accuracy	Test Accuracy
Logistic Regression	[Insert Value]	[Insert Value]
Random Forest	[Insert Value]	[Insert Value]
Optimal Parameters
Logistic Regression:

Regularization strength: [Value]

Penalty type: [Value]

Solver: [Value]

Random Forest:

Number of trees: [Value]

Maximum depth: [Value]

Minimum samples split: [Value]
