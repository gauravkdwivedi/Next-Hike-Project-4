# Next Hike Project - 4 - Feature Extraction and Price Prediction

## Overview:

Welcome to the Mobile Price Prediction Model project! Our primary objective is to construct an advanced predictive model tailored for estimating mobile phone prices by analyzing their key features. The ultimate aim is to develop a powerful tool that provides valuable insights into the pricing dynamics of mobile phones, empowering users to make well-informed decisions.

# Getting Started:

## Prerequisites:

Before delving into the model-building process, make sure you have the following dependencies:

pandas
- seaborn
- matplotlib
- label encoder from sklearn
- train_test_split from sklearn
- LinearRegression from sklearn
- numpy
- metrics from sklearn
- DecisionTreeRegressor
- RandomForestRegressor
- mean_absolute_error, mean_squared_error, r2_score from sklearn
- SVR from sklearn
- KNeighborsRegressor from sklearn

# Steps for Model Building and Selecting the Best Fit:

1. Data Loading and Inspection:
The initial steps involve loading the dataset and inspecting its structure and data types.

2. Handling Missing Values and Outliers:

Address missing values and outliers in the dataset.

3. Creating New Features:

Explore opportunities to create new features from the existing dataset.

4. Normalizing Datasets:

Normalize the datasets using techniques such as one-hot encoding and label encoding.

5. Determining Feature and Target Variables:

Identify the feature and target variables crucial for model training.

6. Splitting Dataset into Train and Test Sets:

Divide the dataset into training and testing sets for model evaluation.

7. Fitting Different Learning Models:

Experiment with various learning models, including Linear Regression, Decision Tree Regressor, Random Forest Regressor, SVR, and KNeighbors Regressor.

8. Evaluating Model Performance:

Assess the performance of each model using evaluation metrics such as mean absolute error, mean squared error, and R2 score.

# Conclusion:

Upon employing various models on the dataset encoded using One-hot encoder, our analysis revealed that the Linear Regression Model, particularly when augmented with Principal Component Analysis (PCA), emerges as the optimal fit for this specific dataset. This finding positions the Mobile Price Prediction Model project as a reliable tool for gaining insights into mobile phone pricing dynamics and supporting well-informed decision-making."
