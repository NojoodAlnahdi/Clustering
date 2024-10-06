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

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- scikit-learn

You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
