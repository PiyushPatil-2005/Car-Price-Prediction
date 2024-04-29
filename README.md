# Car Price Prediction using Random Forest

This project implements a Random Forest Regression model to predict car prices based on various features. The dataset used in this project is loaded and preprocessed before training the model. 

## Introduction

This project aims to predict car prices using Random Forest Regression, a powerful machine learning algorithm capable of handling both numerical and categorical data. The dataset contains information about various car features, and the model is trained to predict the price of a car based on these features.

## Dataset

The dataset used in this project contains information about different cars, including features such as car name, fuel type, horsepower, engine size, mileage, and price. It is split into features (X) and the target variable (Y), where X contains both numerical and categorical data, and Y represents the car prices.

## Implementation

1. **Loading Dataset:** The dataset is loaded from the local directory and preprocessed to remove unnecessary columns.

2. **Feature Engineering:** The features are split into numerical and categorical columns. Numerical columns are scaled using standard scaling.

3. **Train-Test Split:** The dataset is split into training and testing sets with a ratio of 80:20.

4. **Model Training:** A Random Forest Regression model is trained using the training data.

5. **Model Evaluation:** The trained model is evaluated using the testing data, and the R2 score is calculated to measure its performance.

## Usage

To use this project:

1. Clone the repository:
