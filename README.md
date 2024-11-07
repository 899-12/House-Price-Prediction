# House Price Prediction Using the Boston Housing Dataset 
This project demonstrates how to build a House Price Prediction Model using the Boston Housing dataset. A Linear Regression model is used to predict housing prices based on various features such as crime rate, average number of rooms, nitric oxide concentration, and more. The project includes visualizations like a best-fit line and a pair plot to help understand the relationships in the data and the model's predictions.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Steps to Run](#steps-to-run)
- [Results and Visualizations](#results-and-visualizations)
- [Technologies Used](#technologies-used)

## Project Overview

This project applies **Linear Regression** to predict housing prices based on multiple features.


## Dataset

The dataset used in this project is the **Boston Housing Dataset**, which contains the following features:

- **CRIM**: Crime rate by town
- **ZN**: Proportion of residential land zoned for large lots
- **INDUS**: Proportion of non-retail business acres per town
- **CHAS**: Charles River dummy variable (1 if tract bounds river, 0 otherwise)
- **NOX**: Nitric oxide concentration (parts per 10 million)
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built before 1940
- **DIS**: Weighted distance to employment centers
- **RAD**: Index of accessibility to radial highways
- **TAX**: Full-value property tax rate per $10,000
- **PTRATIO**: Pupil-teacher ratio by town
- **B**: Proportion of Black residents by town
- **LSTAT**: Percentage of lower-status population
- **PRICE**: Median value of owner-occupied homes (target variable)

## Data Loading and Preprocessing

In this step, we load the Boston Housing dataset, handle any missing values, and prepare the data for model training. The target variable is **PRICE**, and we ensure that the dataset is in a suitable format for analysis.

## Exploratory Data Analysis (EDA)

We perform EDA to understand the dataset, check for correlations between features, and explore the relationships between variables visually. We also clean the data by handling missing values, if any, and prepare it for model training.

### Visualizations

- Pair plots to visualize relationships between features and target variables.
- Correlation matrix to understand the correlation between features.

## Model Training

We use **Linear Regression** as the model for predicting house prices. The dataset is split into training and test sets, and the model is trained using the training data.

## Evaluation of Model Performance

The performance of the model is evaluated using various metrics, including:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**

These metrics help us assess the accuracy of the predictions.

## Results and Visualizations

- **Best-Fit Line**: We visualize the regression line for better understanding.
- **Pair Plot**: We also plot a pair plot to examine the relationships between features visually.

## Technologies Used

- **Python**
- **scikit-learn**
- **pandas**
- **matplotlib**
- **seaborn**
