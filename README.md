# Internmeets-Internship-Project-2

Summary
Introduction
Overview of the Dataset:
The dataset includes information on insurance charges based on features such as age, sex, BMI, number of children, smoking status, and region.
Objectives:
Convert categorical values to numerical.
Visualize data to understand feature relationships.
Train and evaluate multiple regression models.
Compare model performance to find the best model.
Data Preprocessing
Converting Categorical Values to Numerical:
Used one-hot encoding for categorical columns: sex, smoker, and region.
Exploratory Data Analysis
Heatmap of Feature Correlations:
The heatmap shows the correlations between features and the target variable charges.
Pair Plots of Features:
Pair plots visualize relationships between different features.
Skewness and Kurtosis:
Histograms show skewness and kurtosis for each numerical feature.
Data Preparation
Splitting and Standardizing Data:
Split the data into training and testing sets.
Standardized the features to ensure they are on the same scale.
Model Training and Evaluation
Models:
Linear Regression
Support Vector Regression (SVR)
Ridge Regression
Random Forest Regression
Evaluation:
Each model was trained on the training data and evaluated on the testing data using Mean Squared Error (MSE) and R2 score.
Hyperparameter Tuning
Using GridSearchCV:
Performed hyperparameter tuning to find the best parameters for SVR, Ridge Regressor, and Random Forest Regressor.
Performance Comparison
Comparing Model Performance:
Compared the performance of all models based on Mean Squared Error (MSE) and R2 score using a bar plot. This helped in identifying the model with the best performance.
This summary provides an overview of the steps and processes involved in the data analysis and modeling workflow. It includes data preprocessing, exploratory data analysis, model training, hyperparameter tuning, and performance comparison.
