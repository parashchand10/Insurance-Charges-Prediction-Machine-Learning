# Insurance-Charges-Prediction-Machine-Learning
---

Project Overview
This project aims to predict medical insurance charges based on various personal and health-related features such as age, BMI, smoking status, and region. The model uses Linear Regression to understand the relationship between input variables and insurance costs.

---
Objectives
Build a predictive model for insurance charges
Analyze feature impact on medical expenses
Improve model performance using preprocessing and feature engineering
Evaluate model using appropriate regression metrics

---
Dataset Description
The dataset contains the following features:

age → Age of the individual
bmi → Body Mass Index
children → Number of dependents
is_smoker → Smoking status (0 = No, 1 = Yes)
region → Residential region
sex → Gender
charges → Medical insurance cost (Target Variable)

--
Data Preprocessing
Handled categorical variables using encoding
Applied feature scaling (Standardization)
Checked for missing values and outliers
Created new features like BMI category

---
Model Used
Linear Regression

---
Model Evaluation

The model was evaluated using:

R² Score → Measures how well the model explains variance
Mean Absolute Error (MAE) → Average prediction error

---
How to Use

Run this command in terminal:
```
pip install -r requirements.txt
```
