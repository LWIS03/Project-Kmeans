# Clustering Algorithms and Evaluation Methods

This project involves the design and experimental analysis of **clustering algorithms**, specifically the **k-means** algorithm and its variants, focusing on evaluating their **efficiency**, **clustering quality**, and finding the **optimal number of clusters (k)**.

## Objectives

1. **Implementation**:
   - Basic **k-means** algorithm.
   - Two advanced variants: **k-means++** (improved initialization) and **k-medoids** (uses medoids instead of centroids).

2. **Quality Control**:
   - **Internal evaluation**: Metrics like Average Silhouette to assess cluster compactness.
   - **External evaluation**: Rand Index to compare clustering results against ground truth or other algorithms.

3. **Optimization**:
   - Determine the **optimal number of clusters (k)** using methods like the **Elbow Method**.

4. **Experimentation**:
   - Compare algorithm performance across datasets.
   - Measure execution time, clustering quality, and consistency.

## Features

- **Internal Quality Metrics**:
  - **Average Silhouette**: Evaluates how well elements fit within their clusters.
  - Computational efficiency improvements using simplified metrics.

- **External Quality Metrics**:
  - **Rand Index**: Measures similarity between clustering results.
  - Efficient implementation using hashing for faster calculations.

- **Synthetic Data Generator**:
  - Generates Gaussian-clustered datasets with user-defined parameters (clusters, dimensions, and points per cluster).

## Experimental Setup

1. **Algorithms**:
   - Compare **k-means**, **k-means++**, and **k-medoids** on provided and synthetic datasets.

2. **Evaluation**:
   - Analyze internal and external quality metrics.
   - Use the **Elbow Method** to find the optimal k.

3. **Execution Times**:
   - Record and compare execution times for each algorithm.

## Results and Conclusions

- **Performance**:
  - **k-means++** offers better initialization and typically converges faster than standard **k-means**.
  - **k-medoids** is more accurate but computationally expensive due to higher complexity.

- **Consistency**:
  - High Rand Index values indicate consistent clustering across algorithms.

- **Optimal k**:
  - The Elbow Method effectively identifies the optimal number of clusters.

This project showcases the strengths and limitations of clustering algorithms, providing a framework for evaluating and improving unsupervised learning models.
