# Ad Click Prediction using Logistic Regression
# Overview
* This project applies Logistic Regression, a popular machine learning algorithm, to predict whether an internet user will click on an advertisement based on user behavior and demographic data.

# Dataset Description
* The dataset contains user engagement and demographic features, including:

Daily Time Spent on Site – Time (in minutes) spent on the website.
Age – Age of the user (in years).
Area Income – Average income of the user's geographical area.
Daily Internet Usage – Average time spent online per day (in minutes).
Ad Topic Line – Headline of the advertisement.
City – User's city.
Male – Whether the user is male (1) or female (0).
Country – User's country.
Timestamp – The time at which the user clicked the ad or closed the window.
Clicked on Ad – Binary target variable (1 if clicked, 0 otherwise).

# Objective
The goal is to build a binary classification model that predicts whether a user will click on an advertisement based on their online behavior and demographic details.

# Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
Algorithm: Logistic Regression
Visualization: Matplotlib, Seaborn

# Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing: Handling missing values, feature selection, and encoding categorical variables.
* Visualizations: Distribution of user behavior, correlation heatmaps, and click patterns.

# Model Training & Evaluation
* Train-Test Split: Splitting data into training and testing sets.
* Logistic Regression Model: Training and predicting ad clicks.

# Performance Metrics:
Accuracy Score
Precision, Recall, F1-Score
Confusion Matrix

# Results & Insights
Identified key factors influencing ad clicks.
Achieved 93% accuracy with Logistic Regression.
Visualized click probability distribution and feature importance.
