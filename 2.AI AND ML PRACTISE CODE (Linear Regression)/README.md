#  Linear Regression

###  Introduction

Linear Regression is one of the most fundamental and widely used algorithms in Machine Learning. It is primarily used for predicting continuous numerical values by establishing a linear relationship between dependent and independent variables. The algorithm assumes that the change in the output variable is proportional to the change in one or more input features. Understanding Linear Regression builds a strong foundation for more advanced models and statistical learning methods.

###  Concept Overview

The goal of Linear Regression is to find the **best-fit line** that minimizes the error between the predicted and actual data points. It follows the mathematical equation:
[
y = β₀ + β₁x + ε
]
where **β₀** is the intercept, **β₁** is the coefficient (slope), and **ε** represents the error term.
Key steps include:

1. **Importing Libraries and Dataset** – Using Pandas and NumPy for data handling and Scikit-learn for modeling.
2. **Exploring Relationships** – Visualizing correlations between variables using scatter plots.
3. **Training the Model** – Applying `LinearRegression()` from Scikit-learn to fit the dataset.
4. **Evaluating Performance** – Measuring model accuracy using R² Score, Mean Squared Error (MSE), or Mean Absolute Error (MAE).

###  Explanation of Code

In this notebook, a dataset is imported and split into independent and dependent variables. After visualizing the data distribution, a **Linear Regression model** is trained using Scikit-learn’s `LinearRegression()` function. The model predicts outcomes based on the input variable and plots a regression line over the data to visualize fit quality. Finally, evaluation metrics such as **R² Score** and **MSE** are computed to assess accuracy and performance.

This implementation demonstrates the essence of supervised learning — understanding relationships between variables and making predictions using a simple yet powerful model.
