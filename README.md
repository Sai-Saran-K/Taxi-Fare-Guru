# Taxi Fare Prediction Project

## Overview

This project aims to predict taxi fare amounts based on various trip attributes using machine learning regression techniques. The dataset used contains detailed trip records including pickup and dropoff locations, timestamps, trip distances, and corresponding fare amounts. By leveraging this data, the project explores different regression models to accurately estimate taxi fares, facilitating more reliable fare predictions for both passengers and drivers.

## Features

- **Dataset**: The dataset consists of a comprehensive collection of taxi trip records, encompassing key details such as pickup/dropoff coordinates, timestamps, distance traveled, and fare amounts.
  
- **Machine Learning Models**: The project employs several regression models to predict taxi fares:
  - **Linear Regression**: A baseline model to establish a straightforward relationship between predictors and fare amounts.
  - **Ridge Regression**: Helps mitigate multicollinearity by adding a penalty to the model coefficients.
  - **Lasso Regression**: Utilizes a regularization technique to promote sparsity among predictors.
  - **Decision Tree Regressor**: Captures non-linear relationships and interactions among features.
  - **XGBoost Regressor**: Boosted ensemble model known for its predictive power and ability to handle complex datasets effectively.

- **Evaluation Metrics**: Performance of the models is assessed using standard regression metrics such as R-squared score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE), providing insights into their accuracy and reliability.

## Project Structure

- **Data Preprocessing**: Includes steps for cleaning the dataset, handling missing values, encoding categorical variables, and feature scaling.
  
- **Model Training**: Utilizes Jupyter Notebooks (`Taxi_Fare_Prediction.ipynb`) to train and fine-tune the regression models. It covers feature engineering, model selection, hyperparameter tuning, and cross-validation to ensure robust performance.
