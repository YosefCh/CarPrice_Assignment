# Car Price Prediction

This project is an exploration of various regression models to predict car prices. The dataset used in this project contains various features of cars, including make, model, type, number of doors, and more. The goal is to build a model that can accurately predict the price of a car based on these features.

## Project Structure

The project begins with data loading and preprocessing, including handling of categorical variables and normalization. It then proceeds to exploratory data analysis, where correlations between features are examined.

## Models

Several regression models are explored in this project:

1. **Linear Regression**: A simple linear regression model serves as a baseline. The performance of this model is then compared with more complex models.

2. **Polynomial Regression**: This model is used to capture any non-linear relationships between the features and the target variable.

3. **Random Forest Regression**: This model is used for its ability to handle complex datasets with many features and non-linear relationships.

4. **Gradient Boosting Regression**: This model is used for its ability to provide high performance and interpretability.

Each model's performance is evaluated using cross-validation. The metrics used to evaluate the models include R-squared, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

## Results

The results section of the notebook includes a summary of the performance of each model, as well as visualizations of the results.

## Usage

To use this notebook, you can install Python, along with the necessary libraries (numpy, pandas, matplotlib, scikit-learn, seaborn). You can then run the notebook cell-by-cell to follow along with the analysis. Alternatively the file can be run on __https://colab.research.google.com/__

## Level

This project is suitable for individuals with an **intermediate** level of understanding in machine learning and Python programming. Familiarity with regression models, data preprocessing, and cross-validation is assumed. The code is well-commented and explained, making it accessible to those who are relatively new to these concepts but have some foundational knowledge. 

