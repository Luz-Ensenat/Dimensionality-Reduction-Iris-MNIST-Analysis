# Dimensionality Reduction with PCA and t-SNE

## Overview

This project explores dimensionality reduction techniques using the Iris and MNIST datasets. The notebook demonstrates how to preprocess data, apply normalization, reduce dimensions using PCA and t-SNE, visualize transformed data, and analyze explained variance.

The goal is to understand how dimensionality reduction helps simplify high-dimensional datasets while preserving the most relevant information.

---

## Datasets

### Iris Dataset

The Iris dataset contains measurements of iris flowers from three different species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

Each sample includes the following features:

* Sepal length
* Sepal width
* Petal length
* Petal width

### MNIST Dataset

The MNIST dataset contains grayscale images of handwritten digits from 0 to 9.

Each image is represented as a set of pixel values and is widely used for machine learning and computer vision tasks.

---

## Techniques Used

### Principal Component Analysis (PCA)

PCA is a linear dimensionality reduction technique that transforms the original dataset into a smaller set of orthogonal components while preserving most of the variance.

The notebook includes:

* PCA reduction to 2 and 3 dimensions
* Visualization of transformed data
* Explained variance analysis
* Cumulative explained variance analysis

### t-Distributed Stochastic Neighbor Embedding (t-SNE)

t-SNE is a non-linear dimensionality reduction technique designed for visualization of high-dimensional data.

The notebook includes:

* t-SNE reduction to 2 dimensions
* Visualization of handwritten digit clusters
* Comparison with PCA results
* PCA + t-SNE combined workflow

---

## Project Workflow

1. Load datasets
2. Explore and visualize the data
3. Normalize features using StandardScaler
4. Apply PCA for dimensionality reduction
5. Analyze explained variance
6. Apply t-SNE for non-linear dimensionality reduction
7. Compare PCA and t-SNE visualizations

---

## Technologies and Libraries

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Results

* PCA provides an efficient linear representation of the data and is useful for variance analysis.
* t-SNE produces much clearer cluster separation for complex and non-linear datasets such as MNIST.
* Combining PCA with t-SNE can significantly reduce computational cost while preserving good visualization quality.

---

## Repository Structure

```text
├── notebooks/
│   └── Dimensionality_Reduction_Iris_MNIST_Analysis.ipynb
├── README.md
└── requirements.txt
