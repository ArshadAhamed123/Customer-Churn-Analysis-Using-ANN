
📈 Churn Analysis Using Telecom Dataset
Overview
This project focuses on predicting customer churn using a telecom dataset from Kaggle.
I implemented an Artificial Neural Network (ANN) model built with Keras (TensorFlow backend) and achieved an accuracy of 77%.

Problem Statement
Customer churn is a major concern for telecom companies. Identifying customers likely to leave can help companies take proactive measures to retain them.
The goal of this project is to build a model that accurately predicts whether a customer will churn based on various features.

Technologies Used
Python

TensorFlow / Keras

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn (for visualization)

Kaggle (dataset source)

Workflow
Data Cleaning

Handled missing values

Converted data types appropriately

Exploratory Data Analysis (EDA)

Visualized churn rates across different features

Identified key factors contributing to churn

Feature Engineering

Encoded categorical variables

Scaled numerical features (using MinMaxScaler)

Model Building

Built an ANN using Keras Sequential API

Tuned layers, activation functions, and optimizer

Model Evaluation

Evaluated the model using accuracy, confusion matrix, and classification report

Results
Final ANN model achieved an accuracy of 77% on the test set.

Key features impacting churn: MonthlyCharges, tenure, Contract Type, and TotalCharges.

How to Run
