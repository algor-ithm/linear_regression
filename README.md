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
```

## Usage
1. Clone repository:
```bash
git clone https://github.com/yourusername/linear_regression.git
```

2. Navigate to the project directory:
```bash
cd linear_regression
```

3. Open the Jupyter notebook:
```bash
jupyter notebook simple_linear_regression_example.ipynb
```

4. Run the cells in the notebook to see implmentation and results.

## Resources

- **Dr. Hyuk Cho**: Provided guidance, resources and code snippets for the project. 
- [Linear Regression From Scratch](https://towardsdatascience.com/linear-regression-from-scratch-cd0dee067f72)
- [Linear Regression From Scratch in Python](https://mubaris.com/posts/linear-regression/)
- [Machine Learning From Scratch](https://github.com/chasinginfinity/ml-from-scratch)
- [Linear Regression with Practical Implementation](https://medium.com/machine-learning-researcher/linear-regression-algorithm-in-machine-learning-87c945019cf1)
- [Linear Regression Notes by Andrew Ng](https://www.coursera.org/learn/machine-learning)
- [Master Polynomial Regression with Easy-to-Follow Tutorials](https://www.analyticsvidhya.com/blog/2021/07/all-you-need-to-know-about-polynomial-regression/#:~:text=Polynomial%20regression%20is%20a%20form,convert%20it%20into%20Polynomial%20regression.)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. 
