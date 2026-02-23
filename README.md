# Insurance_Data
Insurance Cost Prediction using Machine Learning

📌 Project Overview

Insurance companies rely heavily on data-driven decision-making to assess customer risk and determine premium charges. This project focuses on analyzing an Insurance dataset to predict individual medical insurance charges based on personal and demographic factors.

The goal of this project is to build a predictive Machine Learning model that estimates insurance costs accurately. By understanding the relationship between various features such as age, BMI, smoking habits, and region, insurance providers can design fair and optimized pricing strategies.

This project demonstrates end-to-end implementation including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and performance evaluation.

🎯 Problem Statement

Insurance providers need to determine how much premium should be charged to a customer. The challenge is:

Can we predict medical insurance charges based on customer information?

This is a Supervised Learning Regression Problem because:

The target variable (charges) is continuous.

We aim to predict numerical values.

📊 Dataset Description

The dataset contains customer information with the following features:

Age – Age of the policyholder

Sex – Gender (Male/Female)

BMI – Body Mass Index

Children – Number of dependents

Smoker – Smoking status (Yes/No)

Region – Residential area

Charges – Medical insurance cost (Target Variable)

The dataset reflects realistic insurance scenarios and customer demographics.

🛠️ Project Workflow
1️⃣ Data Cleaning

Checked for missing values

Verified data types

Removed duplicates

Handled categorical variables using encoding

2️⃣ Exploratory Data Analysis (EDA)

Distribution of insurance charges

Impact of smoking on charges

Correlation analysis

Visualization using plots and graphs

Key Insight:
Smoking has a strong positive correlation with higher insurance charges.

3️⃣ Feature Engineering

One-hot encoding for categorical features

Feature scaling (if required)

Correlation-based feature selection

4️⃣ Model Building

Implemented multiple regression models:

Linear Regression

Ridge Regression

Lasso Regression

5️⃣ Model Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

The best-performing model was selected based on lowest error and highest R² value.

📈 Results & Insights

Age and BMI moderately impact insurance charges.

Smoking status significantly increases insurance cost.

Regularization techniques helped reduce overfitting.

The final model generalizes well on unseen test data.

💡 Business Impact

This predictive model helps insurance companies:

Design risk-based premium pricing

Improve underwriting decisions

Reduce financial loss

Increase pricing transparency

Enhance customer segmentation

🚀 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📌 Conclusion

This project demonstrates how Machine Learning can be applied to solve real-world insurance pricing problems. By leveraging regression techniques and proper data preprocessing, we can build accurate and interpretable models that support business decision-making.
