# Cars-Dataset-XGBoost
🚗 Cars Dataset Analysis and MSRP Prediction with XGBoost

This repository contains an analysis of a car dataset with a focus on predicting the Manufacturer's Suggested Retail Price (MSRP) using the XGBoost regression model. The goal is to leverage machine learning techniques to accurately predict car prices based on various features such as engine size, horsepower, fuel type, and more.

Dataset
The dataset used in this project contains various features related to cars, such as:

Engine Size: The size of the car's engine in liters.
Horsepower: The power output of the car's engine.
Cylinders: Number of cylinders in the car's engine.
Fuel Type: Type of fuel the car uses (e.g., Gasoline, Diesel).
Weight: The weight of the car.
MPG (City & Highway): Miles per gallon the car achieves in city and highway driving.
MSRP: Manufacturer's Suggested Retail Price, which is the target variable.
Project Structure
notebooks/: Contains Jupyter Notebooks used for data exploration, feature engineering, model training, and evaluation.
data/: Contains the dataset used in this project (if not too large), or a script to download the dataset.
src/: Contains Python scripts for model training, evaluation, and utility functions.
visualizations/: Contains visualizations that illustrate various aspects of the dataset and model performance.
Key Steps and Techniques
Data Preprocessing:

Handling missing values, particularly for the Cylinders column.
Encoding categorical features using techniques like Label Encoding.
Splitting the dataset into training and testing sets for model validation.
Model Training with XGBoost:

Implementation of the XGBoost Regressor for predicting MSRP.
Tuning of hyperparameters such as learning rate, max depth, and number of estimators.
Cross-validation to ensure robust model performance.
Model Evaluation:

Calculating metrics like R² score and Mean Squared Error (MSE) to assess model accuracy.
Visualizing feature importance to understand which variables most influence the MSRP predictions.
Plotting actual vs. predicted prices, residual plots, and more to evaluate model performance.
Data Visualization:

Correlation heatmaps to explore relationships between features.
Pairplots to visualize interactions between features and MSRP.
Box plots and scatter plots to understand the distribution and relationships of key variables.
