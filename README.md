# Clustering Analysis with Hierarchical and K-Means Clustering

## Overview
This project performs clustering analysis on the `wine-clustering.csv` dataset using Hierarchical Clustering and K-Means Clustering. The goal is to group similar data points together and evaluate the quality of clustering using different metrics.

## Dependencies
The following Python libraries are required to run the notebook:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install the necessary dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Dataset
The dataset used in this analysis is `wine-clustering.csv`. Ensure this file is in the working directory before running the notebook.

## Methodology
### 1. Data Preprocessing
- Load the dataset using Pandas.
- Perform exploratory data analysis (EDA) with visualizations.

### 2. Hierarchical Clustering
- Apply hierarchical clustering techniques.
- Visualize dendrograms to determine the optimal number of clusters.

### 3. K-Means Clustering
- Apply the K-Means algorithm to cluster the data.
- Determine the optimal number of clusters using methods like the Elbow method and Silhouette score.

## Evaluation Metrics
To assess the quality of clustering, the following metrics are used:
- Silhouette Score
- Calinski-Harabasz Score

## Usage
Run the Jupyter Notebook (`Task4.ipynb`) step by step to reproduce the clustering analysis and visualizations.

## Results
- Clustering visualizations and metrics are provided in the notebook.
- Insights into the data segmentation using clustering techniques.



