# Waiter-Tips-Prediction-ML

#Tips Prediction with Linear Regression
This repository contains a project that predicts the amount of tips based on various features using Linear Regression. The project is implemented in Python and uses several libraries for data manipulation, visualization, and machine learning.

#Project Overview
The goal of this project is to analyze a dataset of restaurant tips and build a predictive model to estimate the tip amount based on features such as total bill, gender, smoker status, day, time, and party size.

#Data
The dataset used in this project is Tips.csv, which contains the following columns:

total_bill: Total bill amount
tip: Tip amount
sex: Gender of the person paying the bill
smoker: Whether the person is a smoker or not
day: Day of the week
time: Time of the day (Lunch/Dinner)
size: Size of the party

#Exploratory Data Analysis (EDA)
The EDA includes:

Visualization of the distribution of tips
Correlation heatmap between numerical features
Scatter plots and pie charts to visualize relationships between features

#Data Preprocessing
One-Hot Encoding for categorical features
Label Encoding for categorical features

#Model Building
A Linear Regression model is built to predict the tip amount. The dataset is split into training and testing sets, and the model is trained on the training data.

#Model Evaluation
The performance of the model is evaluated using:

Mean Squared Error (MSE)
R-squared score (R2)

#Model Tuning and Improvement
Feature scaling is applied using StandardScaler to improve the model's performance.

#Final Model and Deployment
The final model is saved using joblib for future use.

#Results
The model's performance on the test set is as follows:

Mean Squared Error: 0.6948
R-squared: 0.4441

#Testing the Model
The model is tested on known examples from the dataset to compare true values and predicted values.

#Conclusion
This project demonstrates the process of building a predictive model using Linear Regression. It covers data exploration, preprocessing, model building, evaluation, and saving the final model for deployment.
