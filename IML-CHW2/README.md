# README for IML CHW2

## Project Overview

This assignment is part of the *Introduction to Machine Learning* course.  
The objective of this homework is to implement and analyze three fundamental supervised learning algorithms:

- Linear Regression
- Logistic Regression
- Support Vector Machines (SVM)

The goal is to understand the mathematical foundations, optimization procedures, and practical behavior of these models through implementation and experimentation.

The homework is divided into three main sections.

---

## Structure of the Assignment

### Q1 – Linear Regression

In this section, a linear regression model is implemented to solve a regression problem.

Main steps:

- Data preprocessing and normalization
- Implementation of Linear Regression
- Optimization using Gradient Descent (or analytical solution if required)
- Evaluation using Mean Squared Error (MSE)
- Visualization of prediction results

Key learning concepts:

- Loss functions
- Convex optimization
- Bias–variance trade-off
- Gradient-based learning

---

### Q2 – Logistic Regression

This section focuses on binary classification using Logistic Regression.

Main steps:

- Data preprocessing
- Sigmoid activation implementation
- Cross-entropy loss
- Gradient Descent optimization
- Evaluation using:
  - Accuracy
  - Precision / Recall
  - Confusion Matrix

Key learning concepts:

- Probabilistic interpretation of classification
- Maximum likelihood estimation
- Decision boundaries
- Overfitting and regularization

---

### Q3 – Support Vector Machine (SVM)

In this section, SVM is implemented and evaluated for classification tasks.

Main steps:

- Understanding margin maximization
- Implementing linear SVM
- Using kernel methods (if included)
- Model evaluation and comparison with Logistic Regression

Key learning concepts:

- Hard margin vs soft margin
- Hinge loss
- Kernel trick
- Support vectors

---

## Implementation Details

All implementations are done using:

- **Python**
- Jupyter Notebook environment

Main libraries used:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

Where required, models are implemented from scratch to better understand optimization mechanics.  
In some parts, `scikit-learn` may be used for comparison.

---

## Repository Structure

