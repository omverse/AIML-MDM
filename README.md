# Practical Assignment-03: Performance Evaluation of Regression Model

## Overview

This practical focuses on developing a regression model for a real-world application and evaluating its performance using appropriate regression metrics.

The practical also implements **Gradient Descent optimization for Linear Regression** and analyzes its convergence and performance.

## Problem Statement

Develop regression models for a real-world application such as house price prediction and evaluate their performance using appropriate metrics. Implement Gradient Descent optimization for Linear Regression and analyze its performance.

## Objectives

- Develop a regression model for predicting house prices.
- Evaluate the regression model using **MAE, MSE, RMSE, and R² Score**.
- Implement **Gradient Descent** for Linear Regression.
- Analyze the convergence of Gradient Descent using the cost function.
- Compare the performance of Linear Regression and Gradient Descent.

## Dataset

The dataset used in this practical is `house_price.csv`.

It contains the following attributes:

| Feature | Description |
|---|---|
| `Area` | Area of the house in square feet |
| `Bedrooms` | Number of bedrooms |
| `Age` | Age of the house in years |
| `Price` | House price, used as the target variable |

### Sample Dataset

```text
Area,Bedrooms,Age,Price
850,1,18,3600000
900,1,15,3850000
950,2,12,4200000
1000,2,20,4350000
1050,2,10,4650000
