# Customer Churn Prediction and Retention Strategy

## Project Overview

This project focuses on predicting customer churn for a telecom/subscription-based company using machine learning classification models.

The goal of the project is to identify customers who are likely to leave the company’s service and recommend strategies to improve customer retention.

The project includes:

- Data Cleaning
- Exploratory Data Analysis
- Data Preprocessing
- Classification Model Building
- Model Evaluation
- Churn Risk Analysis
- Retention Recommendations


# Business Problem

Customer churn occurs when customers stop using the company’s service.

Churn is a major business problem because acquiring new customers is more expensive than retaining existing customers.

Predicting churn helps businesses:
- identify high-risk customers
- reduce revenue loss
- improve customer retention
- take preventive actions


# Dataset Description

The dataset contains customer information for a telecom/subscription-based company.

Each row represents one customer.

## Dataset Columns

- CustomerID
- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- Contract
- InternetService
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn


# Data Cleaning and Preprocessing Summary

The following preprocessing steps were performed:

- Removed duplicate rows
- Removed CustomerID column
- Converted TotalCharges to numeric format
- Handled missing values
- Encoded categorical variables
- Scaled numerical features
- Split dataset into training and testing sets


# Exploratory Data Analysis

EDA was performed to understand churn behavior.

## Key Insights

- Customers with month-to-month contracts had higher churn rates.
- Customers with higher monthly charges showed higher churn probability.
- Short-tenure customers were more likely to churn.
- Certain payment methods showed increased churn behavior.


# Models Used

The following classification models were used:

- Logistic Regression
- Decision Tree Classifier


# Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Recall was considered especially important because missing churn-risk customers can result in customer loss and revenue decline.


# Final Model Selection

The final model was selected based on:
- overall performance
- recall score
- business suitability

The selected model provided a good balance between identifying churn-risk customers and prediction accuracy.


# Churn Risk Interpretation

Customers with the following characteristics were more likely to churn:

- short tenure
- month-to-month contracts
- high monthly charges
- certain payment methods

Customers were categorized into:
- High Risk
- Medium Risk
- Low Risk


# Retention Strategy

## High-Risk Customers
- retention discounts
- loyalty programs
- personalized support

## Medium-Risk Customers
- promotional campaigns
- customer engagement offers

## Low-Risk Customers
- loyalty rewards
- long-term benefits


# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


# How to Run the Project

1. Install dependencies


pip install -r requirements.txt

# Conclusion

The project successfully predicted customer churn using machine learning models and identified key churn patterns.
The analysis provided valuable insights into customer behavior and helped generate business strategies for customer retention and churn reduction.