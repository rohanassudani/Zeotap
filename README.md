# Customer Segmentation Analysis

## Overview
This project performs customer segmentation using clustering techniques on customer and transaction data. The goal is to identify distinct customer segments based on their purchasing behavior and demographic information.

## Clustering Methodology
- **Clustering Algorithm**: K-Means Clustering
- **Data Sources**: 
  - `Customers.csv`: Contains customer demographic information.
  - `Transactions.csv`: Contains transaction history for each customer.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) is applied to reduce the feature space for better visualization and clustering performance.

## Results
- **Optimal Number of Clusters**: 8
- **Davies-Bouldin Index**: 0.6316 (indicates the quality of clustering)
- **Silhouette Score**: 0.4568 (measures how similar an object is to its own cluster compared to other clusters)

## Visualizations
The project includes visualizations of the clusters, showing the distribution of customers across the principal components derived from PCA.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
