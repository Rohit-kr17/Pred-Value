# Pred-Value
This repository contains a Python script for predicting housing prices using gradient descent and the normal equation. The script performs data preprocessing, model training, evaluation, and visualization.

## Dataset
The dataset used in this project is the Housing Price dataset (Housing Price data set.csv). It contains various features related to housing properties such as number of bedrooms, bathrooms, and size of the house.

## Features
The script preprocesses the dataset, dropping unnecessary columns and standardizing the data.
It splits the dataset into training and testing sets.
The script provides two methods for predicting housing prices:
Gradient Descent
Normal Equation

## Files
Housing Price data set.csv: The dataset file containing housing price data.
housing_price_prediction.py: The Python script for training the models and making predictions.
README.md: This file providing an overview of the project.

## Usage
Ensure you have Python and the required libraries installed (numpy, pandas, and matplotlib).
Clone this repository to your local machine.
Navigate to the repository directory.
Run the housing_price_prediction.py script.

## Methods
Gradient Descent
The script implements gradient descent to train the model with various regularization parameters (lambda).
It computes the error and selects the optimal lambda that minimizes the error.
The script plots the lambda vs. error graph to visualize the error trend.
Normal Equation
The script uses the normal equation to train the model with different regularization parameters.
It calculates the error and identifies the optimal lambda.
The lambda vs. error graph is plotted for visual analysis.

## Evaluation
The script evaluates the models' accuracy using the mean absolute percentage error.
It displays the predicted prices and actual prices for comparison.

## Results
The script provides insights into model performance and identifies the optimal lambda for both gradient descent and normal equation methods.
The accuracy of the models is calculated and reported.

## Conclusion
This project demonstrates how to predict housing prices using two different methods and highlights the importance of regularization in improving model performance. By exploring various regularization parameters, we can optimize model accuracy and make more accurate predictions.

Feel free to explore the code, dataset, and results provided in this repository. Your feedback and contributions are welcome!
