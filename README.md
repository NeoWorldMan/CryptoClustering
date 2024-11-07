# Crypto Clustering Jupyter Notebook

## Project Overview

The notebook processes cryptocurrency data and applies clustering algorithms to identify potential groupings within the crypto market. It uses the K-Means algorithm for clustering and Principal Component Analysis (PCA) for dimensionality reduction, facilitating the visualization of cluster distributions.

## Dependencies

The following libraries are required to run this notebook:

- pandas: for data manipulation and analysis
- sklearn: for machine learning, including KMeans, PCA, and StandardScaler

## Data

The dataset used includes various price change percentages for different cryptocurrencies across specific periods (e.g., 24 hours, 7 days, 14 days, etc.). The data is loaded from a CSV file, crypto_market_data.csv, located in the Resources directory.

## Data Preprocessing

- Normalization: Uses StandardScaler from scikit-learn to scale the data, ensuring all features have equal importance.
- Dimensionality Reduction: Applies PCA for visualization in a two-dimensional space.

## Clustering

The K-Means algorithm is applied to cluster cryptocurrencies based on their performance metrics. Optimal cluster count is selected based on Elbow Method or predefined criteria.

## Running the Notebook

    1. Ensure all dependencies are installed.
    2. Place the crypto_market_data.csv file in the Resources directory.
    3. Execute cells sequentially to load, preprocess, and visualize the clustering results.

## Expected Outputs

    •    Cluster Assignments: Labels indicating which cluster each cryptocurrency belongs to.
    •    Visualization: 2D scatter plot displaying clustered cryptocurrencies post-dimensionality reduction.
