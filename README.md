# Support Vector Machine (SVM) on Iris Dataset

This repository contains a Python implementation of the **Support Vector Machine (SVM)** algorithm applied to the **Iris dataset**. The goal is to classify Iris flowers into different species based on the features of the flowers (sepal length, sepal width, petal length, and petal width) using an SVM classifier.

## Files in this Repository

- `iris.csv`: The Iris dataset file containing the attributes of the Iris flowers, including sepal and petal measurements, along with the species label.
- `SVM.ipynb`: A Python script that implements the SVM classifier using `scikit-learn`. It performs data loading, preprocessing, model training, and evaluation.

## What is Support Vector Machine (SVM)?

A **Support Vector Machine (SVM)** is a supervised machine learning algorithm used for classification and regression tasks. It works by finding a hyperplane that best separates data points of different classes in a high-dimensional space. SVM is particularly effective in high-dimensional spaces and when the number of dimensions exceeds the number of samples.

### Key Features of SVM:
- **Margin Maximization**: SVM seeks to maximize the margin between different classes by finding the optimal hyperplane.
- **Kernel Trick**: SVM can efficiently handle non-linear data by applying the kernel trick to transform the input data into a higher-dimensional space.
- **Robust to Overfitting**: SVM is known for its ability to generalize well, especially when used with appropriate regularization.

