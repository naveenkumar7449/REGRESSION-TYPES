# REGRESSION-TYPES
# California Housing Prices Regression Analysis

## Project Overview
This repository contains a Jupyter Notebook (`REGRESSION TYPES.ipynb`) that explores various regression techniques to predict median house values using the California Housing Prices dataset. The notebook demonstrates the implementation and evaluation of multiple regression models, including Linear Regression, Ridge Regression, Lasso Regression, Polynomial Regression, Decision Tree Regression, and Random Forest Regression. It includes data preprocessing, model training, evaluation, and visualization of results, making it a comprehensive resource for understanding regression in machine learning.

## Background
Regression is a supervised machine learning technique used to predict continuous target variables based on input features. This project leverages the California Housing Prices dataset to predict house prices, a common regression problem. The dataset includes features such as location, house characteristics, and socioeconomic factors, making it suitable for demonstrating different regression approaches.

## Dataset
The dataset used is the **California Housing Prices** dataset, available from Kaggle. It contains the following key features:
- **longitude**: Longitude of the house location
- **latitude**: Latitude of the house location
- **housing_median_age**: Median age of houses in the block
- **total_rooms**: Total number of rooms in the block
- **total_bedrooms**: Total number of bedrooms in the block
- **population**: Population of the block
- **households**: Number of households in the block
- **median_income**: Median income of households in the block
- **ocean_proximity**: Categorical variable indicating proximity to the ocean
- **median_house_value**: Target variable (continuous) representing the median house value

## Prerequisites
To run the notebook, ensure you have the following dependencies installed:
- Python 3.11
- Jupyter Notebook
- Required Python libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

## Notebook Structure
The notebook is organized as follows:

- **Introduction to Regression**: A brief overview of regression as a supervised learning technique.
- **Data Preprocessing**:
  - Loading the dataset using pandas.
  - Handling missing values by dropping rows with null entries.
  - One-hot encoding the categorical variable `ocean_proximity`.
  - Splitting the data into training and testing sets (80-20 split).
  - Standardizing numerical features using `StandardScaler`.
- **Regression Models**:
  - **Linear Regression**: Models the relationship using a straight line.
  - **Ridge Regression**: Adds L2 regularization to prevent overfitting.
  - **Lasso Regression**: Uses L1 regularization for feature selection.
  - **Polynomial Regression**: Captures non-linear relationships using polynomial features.
  - **Decision Tree Regression**: Models non-linear relationships using a tree-based approach.
  - **Random Forest Regression**: An ensemble method combining multiple decision trees.
- **Model Evaluation**:
  - Each model is evaluated using Mean Squared Error (MSE) and R² Score.
  - Visualizations (scatter plots) compare actual vs. predicted values for each model.
- **Results**: Performance metrics for all models are printed, and visualizations are generated using Matplotlib and Seaborn.

## Acknowledgments
- The California Housing Prices dataset is sourced from Kaggle.
- Built using Python, Scikit-learn, Pandas, Matplotlib, and Seaborn.

- Under the guidance of Victor A I
