# codealpha_Disease_Prediction
Stroke Risk Prediction Using Machine Learning
Project Overview
Stroke is one of the leading causes of death and long-term disability worldwide. Early prediction of stroke risk can help healthcare professionals take preventive measures and improve patient outcomes.

This project develops a machine learning-based stroke prediction system using patient demographic information, medical history, and lifestyle factors.

The model predicts whether a patient is at risk of suffering a stroke based on various health indicators.

Problem Statement
Healthcare organizations collect large amounts of patient data, including age, BMI, glucose levels, smoking habits, hypertension status, and heart disease history. Identifying high-risk patients manually can be time-consuming and prone to human error.

The objective of this project is to build a machine learning model capable of predicting stroke risk using structured healthcare data, enabling earlier intervention and better healthcare decisions.

Dataset
Dataset: Healthcare Stroke Dataset

Number of Records: 5,110

Features:

Gender
Age
Hypertension
Heart Disease
Ever Married
Work Type
Residence Type
Average Glucose Level
BMI
Smoking Status
Target Variable:

Stroke (0 = No Stroke, 1 = Stroke)
Project Workflow
1. Data Collection
Load healthcare stroke dataset
Understand feature distributions
2. Data Cleaning
Remove unnecessary columns
Handle missing values
3. Exploratory Data Analysis (EDA)
Target distribution analysis
Feature distribution analysis
Correlation analysis
Risk factor investigation
4. Data Preprocessing
Label Encoding
Feature Scaling using StandardScaler
Handling class imbalance using SMOTE
5. Model Building
Implemented:

Logistic Regression
Random Forest Classifier
XGBoost Classifier
6. Model Evaluation
Evaluation Metrics:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
7. Model Selection
Compare multiple algorithms and select the best-performing model.

8. Model Saving
Save trained model and scaler using Joblib.

Technologies Used
Python
Pandas
NumPy
Scikit-Learn
XGBoost
Imbalanced-Learn
Matplotlib
Seaborn
Joblib


