#  Multiple Linear Regression

###  Introduction

Multiple Linear Regression is an extension of simple linear regression that allows the prediction of a target variable based on **two or more independent variables**. It helps capture more complex relationships where multiple factors influence the output. This algorithm is particularly useful in real-world cases like predicting house prices, sales forecasts, or student performance, where the outcome depends on several inputs simultaneously.

###  Concept Overview

The mathematical model for Multiple Linear Regression is represented as:
[
y = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ + ε
]
Here, **y** is the dependent variable, **x₁...xₙ** are independent variables, **β** values are the coefficients representing the effect of each feature, and **ε** is the error term.
The main stages in building a multiple regression model include:

1. **Data Loading and Exploration** – Importing and analyzing multiple features influencing the target variable.
2. **Handling Categorical Variables** – Encoding categorical inputs using **One-Hot Encoding**.
3. **Model Training** – Using Scikit-learn’s `LinearRegression()` to fit the multi-feature data.
4. **Backward Elimination (Optional)** – Refining the model by removing statistically insignificant predictors.
5. **Model Evaluation** – Measuring how well the model predicts outcomes using R² Score or Adjusted R².

###  Explanation of Code

In this notebook, the dataset is imported and prepared with both numerical and categorical variables. Categorical features are encoded using **OneHotEncoder**, and the data is split into training and test sets. A **Multiple Linear Regression** model is then trained using Scikit-learn’s `LinearRegression()` to predict the dependent variable based on several independent variables. The notebook also demonstrates how to perform **Backward Elimination** using the `statsmodels` library to identify the most impactful features.

This project highlights how multiple predictors can collectively improve prediction accuracy, giving deeper insights into how various factors influence outcomes in a dataset.
