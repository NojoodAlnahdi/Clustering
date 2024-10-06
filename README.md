# K-Means Clustering Algorithm

## Overview

This project implements a K-Means clustering algorithm from scratch using Python's NumPy, Pandas, Matplotlib, and scikit-learn libraries. The algorithm segments data into distinct clusters based on specified features, enabling efficient data analysis and providing insights into patterns and relationships within the dataset.

## Features

- Developed K-Means clustering algorithm from scratch
- Supports clustering of various datasets, including:
  - Blobs
  - Anisotropicly distributed data
  - Noisy moons
  - Noisy circles
- Evaluation metrics for cluster quality, including:
  - F-measure
  - Normalized Mutual Information (NMI)
  - Rand Index

## Datasets

The project utilizes four different datasets for clustering:

1. **Blobs**: A simple dataset with three well-defined clusters.
2. **Anisotropicly Distributed Dataset**: A dataset that is transformed to create an elongated shape, testing the algorithm's effectiveness on non-spherical clusters.
3. **Noisy Moons**: A dataset with two interleaving half circles, adding complexity due to noise.
4. **Noisy Circles**: A dataset with two concentric circles, further challenging the clustering algorithm.


## Code Explanation
**KMeans Class**
Initialization: Sets up the number of clusters and initializes parameters.
_initialize_centroids: Randomly selects initial centroids from the dataset.
_assign_clusters: Assigns each data point to the nearest centroid.
_update_centroids: Recalculates centroids as the mean of assigned data points.
_predict: Returns the final cluster assignments.
_plot: Visualizes the clustering results.
fit: Executes the K-Means algorithm by iteratively assigning clusters and updating centroids.

**Evaluation Metrics**
The project includes validation of the clustering results using three metrics:

F-measure: Balances precision and recall to evaluate cluster quality.
Normalized Mutual Information (NMI): Measures the agreement between true labels and predicted clusters.
Rand Index: Assesses the similarity between the predicted and actual labels.
