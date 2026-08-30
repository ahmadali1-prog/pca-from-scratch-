# PCA From Scratch — Iris Dataset

## Overview

This project implements Principal Component Analysis (PCA) from scratch using Python and linear algebra.

The goal is to understand how PCA reduces the dimensionality of a dataset while preserving as much information as possible.

## Dataset

The Iris dataset contains 150 observations with four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The `Id` and `Species` columns are excluded from the PCA calculations.

## Method

PCA was implemented through the following steps:

1. Feature selection
2. Z-score standardization
3. Covariance matrix calculation
4. Eigenvalue and eigenvector decomposition
5. Sorting principal components by explained variance
6. Selecting PC1 and PC2
7. Projecting the 4-dimensional data into 2 dimensions
8. Visualizing the transformed data
9. Validating the results using Scikit-learn

## Results

- PC1 explained approximately **72.77%** of the variance.
- PC2 explained approximately **23.03%** of the variance.
- Together, PC1 and PC2 retained approximately **95.80%** of the total variance.

This allowed the original four-dimensional dataset to be represented using two principal components while retaining most of its variance.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Concepts

- Principal Component Analysis
- Z-score standardization
- Covariance
- Eigenvalues and eigenvectors
- Explained variance
- Matrix projection
- Dimensionality reduction

## Validation

The from-scratch implementation was compared with Scikit-learn's PCA implementation to verify the explained variance results.
