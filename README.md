# House Price Prediction using Linear Regression

## Overview

This project uses Linear Regression to predict house values using
the California Housing Dataset.

## Dataset

The California Housing Dataset is provided through scikit-learn.

It contains 20,640 samples and 8 predictive features.

The target variable is the median house value.

## Features

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

## Methodology

1. Load the dataset
2. Explore the data
3. Check for missing values
4. Separate features and target
5. Split data into training and testing sets
6. Train Linear Regression model
7. Generate predictions
8. Evaluate using RMSE, MAE and R²
9. Analyze residuals
10. Save the trained model

## Evaluation

The model is evaluated using:

- RMSE
- MAE
- R² Score

See `evaluation_metrics.csv` for the obtained results.

## Visualizations

The project includes:

- Residual plot
- Actual vs Predicted plot

## Model Artifact

The trained model is saved as:

`house_price_linear_regression.pkl`

## Reproduction

Open the notebook:

`house_price_prediction_linear_regression.ipynb`

Run the cells from top to bottom.

The California Housing Dataset is loaded automatically using
scikit-learn.

## Sample Predictions

Sample actual and predicted values are available in:

`sample_predictions.csv`
