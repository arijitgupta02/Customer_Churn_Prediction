# Customer Churn Prediction

## Overview

This project focuses on predicting customer churn in a telecom company using Machine Learning techniques. The goal is to identify customers who are likely to leave the service based on customer demographics, account information, and service usage patterns.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, handling imbalanced data using SMOTE, model training, evaluation, and prediction.

---

## Dataset

Dataset Used: Telco Customer Churn Dataset

Target Variable:
- Churn (Yes / No)

The dataset contains customer information such as:
- Gender
- Senior Citizen Status
- Tenure
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Handling Imbalanced Data using SMOTE
7. Model Training
8. Model Evaluation
9. Customer Churn Prediction

---

## Exploratory Data Analysis

The project includes:
- Churn Distribution Analysis
- KDE Plots
- Count Plots
- Box Plots
- Correlation Heatmap
- Feature Relationship Analysis

---

## Machine Learning Model

Model Used:
- Random Forest Classifier

The model was trained after:
- Encoding categorical features
- Scaling numerical features
- Balancing classes using SMOTE

---

## Evaluation Metrics

The model performance was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score
- ROC Curve

---

## Project Structure

```text
customer-churn-prediction/
│
├── Customer_Churn.ipynb
├── README.md
├── requirements.txt
├── Telco-Customer-Churn_Dataset.csv
