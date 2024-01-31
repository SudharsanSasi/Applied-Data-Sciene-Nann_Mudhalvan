

# Customer Segmentation using Applied Data Science

This repository contains code for performing customer segmentation and clustering analysis on the Mall Customers dataset using Python, Pandas, Scikit-Learn, and Matplotlib.

## Overview

The primary objective of this project is to gain insights into customer behavior and segment Mall Customers based on their spending patterns. Customer segmentation is a valuable marketing and business strategy, helping businesses understand their customer base better and tailor their services and marketing efforts accordingly. This codebase accomplates the following key steps:

### Data Preprocessing

- Imports essential libraries, including Pandas, NumPy, Matplotlib, and Scikit-Learn.
- Reads the 'Mall_Customers.csv' dataset, which contains valuable customer information such as age, annual income, and spending score.
- Handles missing values using a mean imputation strategy to ensure data integrity.
- Scales the data using StandardScaler to prepare it for clustering analysis.
- Visualizes the data using t-SNE (t-Distributed Stochastic Neighbor Embedding), reducing the data to two dimensions for visual inspection.

### Clustering

- Implements K-Means clustering, a popular unsupervised machine learning algorithm, to group customers into distinct clusters.
- Adds cluster labels to the original dataset, which can be used for further analysis or targeted marketing efforts.

### Training and Testing

- Splits the data into training and testing sets, enabling the model to generalize well.
- Utilizes K-Means clustering on the training set and then predicts clusters for the testing set, assessing how well the model generalizes to new, unseen data.

### Visualization

- Displays a scatter plot of the testing data points, color-coded by their predicted cluster labels. This visualization provides a clear representation of how customer segments are distributed in the dataset.

### Evaluation

- Calculates the Silhouette Score, a metric that quantifies the quality of the clustering. A higher Silhouette Score indicates better-defined clusters.
- Computes the inertia (within-cluster sum of squares) for both the training and testing data, giving insights into the tightness of the clusters. Lower inertia values suggest better-defined clusters.

## Requirements

Before running the code, ensure that you have the following Python libraries installed:

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
