#  K-Means Clustering

###  Introduction

K-Means Clustering is one of the most popular **unsupervised machine learning algorithms**, primarily used for **data segmentation and pattern discovery**. Unlike supervised models, it does not rely on labeled data. Instead, it groups similar data points into clusters based on their features. K-Means is widely used in applications like customer segmentation, image compression, and anomaly detection.

###  Concept Overview

The algorithm aims to partition the dataset into **K distinct clusters**, where each data point belongs to the cluster with the nearest mean (centroid). The process involves iterative optimization until cluster assignments stabilize.
Key steps include:

1. **Choosing the Number of Clusters (K)** – Selecting K using methods like the **Elbow Method**.
2. **Initializing Centroids** – Randomly assigning initial cluster centers.
3. **Assignment Step** – Allocating each data point to the nearest centroid.
4. **Update Step** – Recalculating centroid positions based on assigned points.
5. **Convergence** – Repeating steps until centroids stop moving significantly.

###  Explanation of Code

In this notebook, the dataset is first preprocessed and visualized. The **Elbow Method** is implemented to determine the optimal number of clusters by plotting the within-cluster sum of squares (WCSS). Then, the **KMeans** algorithm from Scikit-learn’s `cluster` module is applied to group the data. The resulting clusters and centroids are visualized using Matplotlib, showing clear separation between groups.

This notebook effectively demonstrates how K-Means identifies natural patterns in unlabeled data, giving valuable insights into underlying structures. It also shows how to evaluate and visualize clusters — essential skills in unsupervised learning and exploratory data analysis.
