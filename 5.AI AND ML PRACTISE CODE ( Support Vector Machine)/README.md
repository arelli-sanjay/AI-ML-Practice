#  Support Vector Machine (SVM)

### Introduction

Support Vector Machine (SVM) is a powerful **supervised machine learning algorithm** used for both classification and regression tasks, but it is most commonly applied to **classification problems**. SVM works by finding the optimal hyperplane that best separates data points of different classes. It is highly effective for high-dimensional spaces and is widely used in applications like image recognition, text classification, and bioinformatics.

###  Concept Overview

The main idea behind SVM is to find a boundary (hyperplane) that maximizes the **margin** between two classes. The points closest to this hyperplane are called **support vectors**, as they define the position of the boundary.
Key concepts include:

1. **Hyperplane and Margin** – The hyperplane separates classes; the margin is the distance between the hyperplane and the nearest data points.
2. **Kernel Trick** – Transforms non-linearly separable data into higher dimensions using kernels (Linear, Polynomial, RBF).
3. **Model Training** – Uses Scikit-learn’s `SVC()` to train the SVM classifier.
4. **Evaluation** – Performance measured using Accuracy, Confusion Matrix, and Classification Report.
5. **Visualization** – Plotting the decision boundary for a better understanding of class separation.

###  Explanation of Code

In this notebook, the dataset is first preprocessed using encoding and scaling techniques. Then, an **SVM classifier** is built using Scikit-learn’s `SVC()` with different kernel functions such as **linear** and **RBF** to evaluate performance across varying data patterns. The model is trained on the training set and evaluated on the test set using accuracy metrics. Additionally, decision boundaries are visualized to show how the SVM separates the data classes with maximum margin.

This notebook highlights the strength of SVMs in handling both linear and non-linear data distributions and demonstrates their effectiveness in achieving accurate and robust classification results.
