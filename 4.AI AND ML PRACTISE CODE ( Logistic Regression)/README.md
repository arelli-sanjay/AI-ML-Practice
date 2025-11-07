#  Logistic Regression

###  Introduction

Logistic Regression is one of the most widely used algorithms for **classification problems** in Machine Learning. Unlike Linear Regression, which predicts continuous outcomes, Logistic Regression predicts **categorical outcomes** — such as yes/no, spam/ham, or true/false. It estimates the probability that a given input belongs to a certain class using the logistic (sigmoid) function. Understanding Logistic Regression is crucial because it forms the basis for many advanced classification algorithms.

###  Concept Overview

The logistic model transforms linear outputs into probability values between 0 and 1 using the **sigmoid function**:
[
P(y=1) = \frac{1}{1 + e^{-(β₀ + β₁x₁ + ... + βₙxₙ)}}
]
Key steps include:

1. **Data Import and Exploration** – Loading and visualizing the dataset to understand class distribution.
2. **Feature Preprocessing** – Handling missing values, encoding categorical data, and scaling features.
3. **Model Building** – Using Scikit-learn’s `LogisticRegression()` to train a binary classification model.
4. **Prediction and Evaluation** – Evaluating performance using Accuracy, Confusion Matrix, and Classification Report.
5. **Decision Boundary Visualization (Optional)** – Visualizing how the classifier separates different categories.

###  Explanation of Code

In this notebook, the dataset is preprocessed and split into training and testing sets. A **Logistic Regression model** is implemented using `LogisticRegression()` from Scikit-learn. After training, predictions are made on the test set, and model performance is evaluated using metrics like **Accuracy Score** and **Confusion Matrix**. The notebook also includes visualization of decision regions to show how the classifier distinguishes between classes.

Through this implementation, the project demonstrates how logistic regression converts linear outputs into probabilities and makes reliable binary predictions — a foundation for advanced AI and ML classification models.
