# Linear Regression

A simple linear regression model implemented using the least squares method from scratch and then using `sklearn`. The model is applied to brain data.

## Overview

This project demonstrates the implementation of a linear regression model using the least squares method in Python from scratch. Additionally, it uses the `sklearn` library to perform linear regression on the same dataset for comparison. The brain dataset used in this project is provided.

## Table of Contents

- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Implementation](#implementation)
  - [From Scratch](#from-scratch)
  - [Using sklearn](#using-sklearn)
  - [Polynomial Regression](#polynomial-regression)
- [Results](#results)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
- `simple_linear_regression.ipynb`: Jupyter notebook containing the implementation of the linear regression model from scratch and using 'sklearn'.
- `headbrain.csv`: Dataset used for linear regression model.
- `README.md`: Project Documentation.

## Dataset

The dataset used is 'headbrain.csv', which contains measurements of head size and brain weight. The columns in the dataset are:
- `Gender`
- `Age Range`
- `Head Size(cm^3)`
- `Brain Weight(grams)`

## Implementation

### From Scratch

The linear regression model is first implemented from scratch using Python. The least squares method is used to calculate the best-fit line for the given data. The process involves:
1. Calculating the mean of the input (X) and output (Y) variables.
2. Computing the slope (m) and intercept (b) of the line.
3. Using the slope and intercept to predict Y values for given X values.

### Using sklearn

The `sklearn` library is then utilized to perform linear regression on the same dataset. The steps include:
1. Importing the `LinearRegression` model from `sklearn`.
2. Fitting the model to the dataset.
3. Making predictions and comparing them with the from-scratch implementation.

### Polynomial Regression

Polynomial regression is also implemented to demonstrate how non-linear data can be fitted using polynomial features. The steps include:
1. Creating polynomial features from the input data.
2. Fitting a polynomial regression model.
3. Making predictions and visualizing the results.

## Results

The results section compares the predictions made by the from-scratch implementation, the `sklearn` model, and polynomial regression, highlighting any differences and similarities. It includes visualizations of the data and the regression lines.

## Dependencies

- Python 3.x
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- sklearn

Install the dependencies using:
```bash
pip install numpy pandas matplotlib sklearn jupyter