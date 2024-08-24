# Zidio_Project_1
# K-means Clustering Analysis

This project demonstrates K-means clustering, a popular unsupervised machine learning algorithm, applied to a scaled dataset. The analysis includes cluster visualization and silhouette analysis for evaluating the clustering quality.

## Overview

K-means clustering is used to partition the data into a predefined number of clusters (in this case, 3 clusters). The goal is to minimize the distance of data points from the centroids of their respective clusters.

## Steps in the Analysis

1. **Data Preparation:**
   - The dataset is scaled using a MinMax scaler to ensure all features contribute equally to the clustering process.

2. **K-means Model Creation and Fitting:**
   - The K-means model is created with 3 clusters and fitted to the scaled data.

3. **Cluster Assignment:**
   - After fitting, the data points are assigned cluster labels, and the cluster centers are determined.

4. **Cluster Visualization:**
   - A scatter plot is used to visualize the clusters in the dataset. The cluster centers are marked for reference.

5. **Silhouette Analysis:**
   - The silhouette score, which measures how similar each point is to its own cluster compared to other clusters, is calculated.
   - A silhouette plot is created to visualize the silhouette scores for each data point, with the average silhouette score indicated.

## Visualizations

- **Scatter Plot:** Displays the clustered data points with different colors representing different clusters, and red 'X' markers representing the cluster centers.
- **Silhouette Plot:** Visualizes the silhouette coefficient for each sample, showing how well-separated the clusters are.

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/chaithu10000/Zidio_Project_1.git
   cd Zidio_Project_1

