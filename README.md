# CryptoClustering

## Table of contents

* [Overview](#Overview)
* [Key Objectives](#Key-Objectives)
* [Steps](#Steps)
* [Results and Insights](#Results-and-Insights)
* [Key Question Answered](#Key-Question-Answered)
* [Questions](#Questions)
* [References](#References)

## Overview

This project demonstrates the use of K-Means clustering to analyze and group cryptocurrencies based on market data. Dimensionality reduction using Principal Component Analysis (PCA) is employed to evaluate its impact on the clustering process. Visualizations are provided to compare results from clustering the original and reduced datasets.

## Key Objectives

1. Preprocess the cryptocurrency market data for clustering. 
2. Use the Elbow Method to determine the optimal number of clusters (“k”).
3. Compare cluster analysis results between the original dataset and PCA-reduced dataset. columns:

## Steps

1. **Data Preprocessing**

* Load the dataset and inspect its structure.
* Normalize the data using StandardScaler to standardize feature magnitudes.
* Select relevant columns (e.g., price changes across time intervals) for analysis.

2. **Clustering with Original Data**

* Implement the Elbow Method to determine the optimal number of clusters.
* Apply K-Means clustering to the normalized data.
* Visualize the Elbow Curve for the original data.

3. **Dimensionality Reduction with PCA**

* Apply PCA to reduce the dataset’s dimensionality to 2 components.
*-* Recompute the Elbow Curve and apply K-Means clustering to the PCA-reduced data.

4. **Comparison**

* Generate composite visualizations to compare the Elbow Curves and clustering results of the original and PCA-reduced datasets.

## Results and Insights

* **Original Data:** Provided a detailed clustering structure but may include noise or redundant information.

* **PCA-Reduced Data:** Improved clustering performance and clarity with fewer features, at the potential cost of losing some data granularity.

## Key Question Answered

**What is the impact of using fewer features to cluster the data using K-Means?**

Using fewer features, after applying PCA, simplifies the cluster structure, reduces overfitting, and improves computational efficiency. 

## Questions

In case of any additional questions please visit my GitHub link: [Feda](https://github.com/Feda2020)

## References

* Stach Overflow (https://stackoverflow.com/)
* Xpert Learning (https://bootcampspot.com)