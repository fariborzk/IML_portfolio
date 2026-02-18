# README for IML CHW3

## Project Overview

This assignment is part of the *Introduction to Machine Learning* course.  
The objective of this homework is to explore advanced machine learning techniques, focusing on dimensionality reduction, clustering, and probabilistic models.

The assignment emphasizes implementing algorithms from scratch to gain a deeper understanding of unsupervised learning methods and their mathematical foundations.

The homework is divided into two major components:

- PCA and K-Means
- Gaussian Mixture Model (GMM) using Expectation-Maximization (EM)

---

## Structure of the Assignment

### Part 1 – Principal Component Analysis (PCA) and K-Means

This section focuses on dimensionality reduction and clustering.

Main steps:

- Implement PCA from scratch using linear algebra
- Compute covariance matrix and eigen decomposition
- Project data into lower-dimensional space
- Apply K-Means clustering
- Compare clustering performance before and after PCA

Key learning concepts:

- Variance maximization
- Eigenvalues and eigenvectors
- Dimensionality reduction
- Distance-based clustering
- Effect of feature transformation on clustering

---

### Part 2 – Gaussian Mixture Model (GMM) using EM

This section focuses on probabilistic clustering using GMM.

Main steps:

- Implement GMM from scratch
- Initialize means, covariances, and mixing coefficients
- Implement Expectation (E-step)
- Implement Maximization (M-step)
- Compute log-likelihood
- Monitor convergence behavior

Key learning concepts:

- Latent variable models
- Maximum likelihood estimation
- EM algorithm
- Soft clustering vs hard clustering
- Probabilistic interpretation of clustering

---

## Implementation Details

All implementations are done using:

- **Python**
- Jupyter Notebook environment

Main libraries used:

- `numpy`
- `matplotlib`
- `pandas`
- `scikit-learn` (for comparison when required)

Core algorithms (PCA and EM) are implemented manually to reinforce theoretical understanding.

---

## Repository Structure

