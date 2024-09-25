# Principal-Component-Analysis


Principal Component Analysis (PCA) is a widely used dimensionality reduction technique in statistics and machine learning. It transforms data into a set of linearly uncorrelated variables called "principal components." The main goal of PCA is to reduce the number of features or dimensions in a dataset while retaining as much variance (information) as possible.This README is providing an overview of PCA and demonstrating its implemented steps.

# implimented steps

#import necessary package
importing numpy as np 
NumPy (Numerical Python) is a powerful open-source library in Python, primarily used for numerical and scientific computing. It provides support for large, multi-dimensional arrays and matrices, along with a vast collection of mathematical functions to operate on these arrays efficiently.

#Step one(Standardization)
In PCA, it is essential to standardize data because PCA identifies the directions of maximum variance, which can be biased if features are on different scales. Without standardization, features with larger magnitudes will dominate the principal components, leading to skewed results. Standardization ensures that all features contribute equally by rescaling them to have a mean of 0 and a standard deviation of 1, allowing PCA to capture the true underlying patterns and relationships in the data, rather than being influenced by the differences in scale.

#Step two (calculate the covariance matrix)
We calculate the covariance matrix in PCA to measure how different features in the dataset vary together. It helps identify relationships between variables and determines the directions (principal components) where the data has the most variance. This allows PCA to capture the most informative aspects of the data by focusing on the directions with the highest covariance

#Step three (Eigendecomposition on the Covariance Matrix)
Calculating eigendecomposition on the covariance matrix in PCA helps to find the eigenvectors (principal components) and eigenvalues, which represent the directions of maximum variance and the magnitude of variance along those directions, respectively. The eigenvectors define the new feature space, while the eigenvalues indicate how much variance is captured by each principal component, enabling dimensionality reduction by focusing on the most important components.

#Step four (Sort the Principal Components)

We sort the principal components in PCA based on their corresponding eigenvalues to prioritize the components that capture the most variance in the data. Principal components with larger eigenvalues represent directions of greater variance and hold more significant information. Sorting allows us to focus on the most informative components and reduce dimensionality by discarding those with lower variance, simplifying the data while retaining its essential structure.

#Step five ()



