# House-Price-Prediction README

## Table of Contents
- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Data Overview](#data-overview)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)


## Introduction

This project aims to predict house prices based on various features such as average area income, house age, number of rooms, number of bedrooms, and population of the area. The dataset used for this project is stored in the file `USA_Housing.csv`.

## Libraries Used

- `numpy`: A library for numerical computations in Python.
- `seaborn`: A visualization library based on Matplotlib that provides a high-level interface for drawing attractive statistical graphics.
- `pandas`: A data manipulation and analysis library.
- `matplotlib`: A comprehensive library for creating static, animated, and interactive visualizations in Python.
- `scipy`: A library for scientific and technical computing.
- `sklearn`: A machine learning library providing tools for data analysis and modeling.

## Data Overview

The dataset used contains information about various houses in the USA. It includes features like average area income, house age, number of rooms, number of bedrooms, area population, and the corresponding house prices.

## Data Preprocessing

- Checked for missing values: There were no missing values in the dataset.
- Correlation analysis: Explored the relationships between features using a heatmap.

## Model Building

- Linear Regression Model: The project employs a Linear Regression model for predicting house prices.

## Model Evaluation

- Mean Absolute Error (MAE): A metric used to evaluate the performance of the model.
- Mean Squared Error (MSE): Another metric to assess model performance.
- Root Mean Squared Error (RMSE): A measure of the average deviation between predicted and actual values.

## Results

- The model was able to predict house prices with a certain level of accuracy.

## Visualizations

- Distribution plot of house prices.
- Scatter plot comparing actual prices with predicted prices.

## Conclusion

This project demonstrates the successful application of a Linear Regression model for predicting house prices based on relevant features. The model's performance was evaluated using MAE, MSE, and RMSE, providing insights into its accuracy.

Please note that this readme provides an overview of the project. For detailed code and analysis, refer to the corresponding Python script.
