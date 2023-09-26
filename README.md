# Online Payments Fraud Detection - Blossom Bank

## Introduction

Payment fraud is a major issue in the banking system, with losses amounting to trillions of dollars globally. The increased volume of electronic transactions has resulted in an increase in fraudulent activities. Blossom Bank, a multinational financial services group, wants to build a machine learning model to predict online payment fraud and improve its cybersecurity policies. The goal of this project is to effectively detect and identify anomalies in transactions that would normally be undetected using traditional methods and prevent fraudulent transactions.

## Problem Statement

Blossom Bank wants to build a machine learning model to predict online payment fraud. Fraudulent activities can cost the bank significant amounts of money and can erode customer trust in the platform. The bank wants to use machine learning to detect fraudulent transactions and improve its cybersecurity policies. 

## Methodology

The following methodology was used in this project:

1. Importing Libraries: Libraries such as Pandas, Numpy, Matplotlib, and Seaborn were imported for data manipulation and visualization.

2. Loading the Dataset: The dataset was loaded using pd.read_csv() from the local computer.

3. Exploratory Data Analysis: The dataset was explored to identify columns, unique values, missing values, shape of the entire dataset, info of the columns and data types, and statistical analysis of the data. Outliers were also identified in the dataset.

4. Relationship, Insights, and Visualizations: Univariate, bivariate, and multivariate analysis techniques were used to visualize the data and create a function that properly labels fraud transactions. Transaction types in relation to transaction amount and fraud status were analyzed.

5. Feature Engineering: Categorical variables were encoded to convert them into numerical values so that they can be featured or implemented in the machine learning model. The target feature, fraud_trans, was dropped.

6. Model Preparation and Deployment: Supervised machine learning models (classification and regression) Linear Regression, Random Forest, and Decision Tree were deployed. Of the three models, Random Forest was the most accurate at detecting fraudulent transactions. The confusion matrix also showed that it had the highest true positive rate.

7. Evaluating with Cross Validation: The model was evaluated using cross-validation to determine how it would perform when it sees new data in the real world that it hasn't seen before.

8. Model Deployment: The model was deployed for use by Blossom Bank to detect fraudulent transactions and improve its cybersecurity policies.

## Conclusion

This project demonstrates how machine learning can be used to effectively detect fraudulent transactions in the banking system. By building a machine learning model, Blossom Bank can prevent fraudulent activities that can cost significant amounts of money and erode customer trust in the platform. The Random Forest model was found to be the most accurate at detecting fraudulent transactions, and it can be used by Blossom Bank to improve its cybersecurity policies.