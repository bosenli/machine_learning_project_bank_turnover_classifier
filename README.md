# machine_learning_project_bank_turnover_classifier

The Dataset: Bank Customer Churn Modeling

Problem statement: Given a Bank customer, can we build a classifier which can determine whether they will leave in the next 6 months or not?

DataSet URL: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling/version/1?select=Churn_Modelling.csv

Overview: Using Python for Customer Churn Prediction
Python comes with a variety of data science and machine learning libraries that can be used to make predictions based on different features or attributes of a dataset. Python's SCIKIT-LEARN library is one such tool. In this article, we'll use this library for customer churn prediction.

The Dataset: Bank Customer Churn Modeling
The dataset you'll be using to develop a customer churn prediction model can be downloaded from this KAGGLE LINK. Be sure to save the CSV to your hard drive.

Taking a closer look, we see that the dataset contains 14 columns (also known as features or variables). The first 13 columns are the independent variable, while the last column is the dependent variable that contains a binary value of 1 or 0. Here, 1 refers to the case where the customer left the bank after 6 months, and 0 is the case where the customer didn't leave the bank after 6 months. This is known as a binary classification problem, where you have only two possible values for the dependent variable—in this case, a customer either leaves the bank after 6 months or doesn't.

It's important to mention that the data for the independent variables was collected 6 months before the data for the dependent variable, since the task is to develop a machine learning model that can predict whether a customer will leave the bank after 6 months, depending on the current feature values.

You can use MACHINE LEARNING classification algorithms to solve this problem.

Note: All the code in this article is executed using THE SPYDER IDE FOR PYTHON.

Here's an overview of the steps we'll take in this article:

Importing the libraries
Loading the dataset
Selecting relevant features
Converting categorical columns to numeric ones
Preprocessing the data
Training a machine learning algorithm
Evaluating the machine learning algorithm
Evaluating the dataset features
