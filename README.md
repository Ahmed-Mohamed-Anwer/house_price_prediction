# Housing Value Prediction

This notebook explores a California housing dataset and builds predictive models to estimate median house values.

## Overview

The goal of this project is to analyze the factors influencing housing prices and develop a model that can predict median house values based on various features.

## Dataset

The dataset used in this notebook contains information about housing in California, including:

- Latitude and Longitude
- Median age of houses
- Total rooms and bedrooms
- Population and households
- Median income
- Median house value (target variable)
- Ocean proximity

## Analysis and Modeling

The notebook performs the following steps:

1. **Data Exploration and Preparation**:
    - Loading and inspecting the data.
    - Handling missing values (imputing with the mean).
    - Analyzing data distributions using histograms.
    - Visualizing correlations between features using a heatmap.
    - Exploring the relationship between geographical location, housing age, and median house value.
    - Performing one-hot encoding for the categorical 'ocean_proximity' column.

2. **Building Predictive Models**:
    - Splitting the data into training and testing sets.
    - Training and evaluating two regression models:
        - Linear Regression
        - Random Forest Regressor
    - Comparing the performance of the models using R2 score and Mean Squared Error.

## Results

The Random Forest Regressor model achieved better results compared to the Linear Regression model on this dataset.
