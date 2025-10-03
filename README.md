# Principal-Component-Analysis
PCA-Transformed Data

## Overview
This part of the project applies PCA to reduce dimensionality before performing clustering.
The aim is to improve clustering quality by removing redundancy and noise while retaining most of the variance.

## Steps
1. Apply PCA to the dataset to extract principal components.
2. Choose the number of components based on cumulative explained variance (e.g., 90–95% variance retained).
3. Perform K-Means clustering on the PCA-transformed dataset.
4. Evaluate clustering performance using Silhouette Score.
5. Visualize clusters in 2D and 3D PCA space for interpretability.

## Key Insights
- PCA helps simplify complex, high-dimensional datasets.
- Clusters become more distinct and easier to visualize.
- Small variance information may be lost, but clustering often improves in quality and stability.
- Useful for high-dimensional datasets (images, text embeddings, genomics, etc.).
