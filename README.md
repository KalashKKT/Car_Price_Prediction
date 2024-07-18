# Car Price Prediction

This project aims to predict the selling price of used cars based on various features using machine learning models. By leveraging data on car characteristics and historical prices, we can provide accurate price predictions to assist both sellers and buyers in the used car market.


## Overview

The dataset includes features such as:
- **Present Price**: Current ex-showroom price of the car.
- **Kms Driven**: The distance completed by the car in kilometers.
- **Fuel Type**: The type of fuel used by the car (Petrol, Diesel, CNG).
- **Seller Type**: Whether the seller is a dealer or an individual.
- **Transmission**: The transmission type of the car (Manual/Automatic).
- **Owner**: The number of owners the car has had.
- **Year**: The year the car was bought.

## The project workflow involves:
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Understanding the data through visualization.
- **Model Training and Evaluation**: Using Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regression.
- **Hyperparameter Tuning**: Optimizing the models for better performance.
- **Model Saving**: Saving the best model using pickle for future predictions.


## Models and Results
-**Linear Regression**:
MAE: 1.140
R²: 0.861

-**Random Forest Regression**:
MAE: 0.513
R²: 0.971
