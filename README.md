# KMeans-Clustering-Normalization-Analysis
This repository contains an implementation of K-Means clustering to explore the effect of data normalization. Two datasets—`iris.csv` and `kmtest.csv`—are used to analyze the impact of normalization on the clustering results. The task involves applying K-Means on both normalized and non-normalized datasets, comparing the results, and measuring the similarity between clusters.

## Features

- K-Means clustering on two datasets:
  - **Iris dataset**: Classic dataset containing iris flower characteristics and species.
  - **KMTest dataset**: A custom dataset for testing clustering.
  
- Analysis of the impact of normalization on clustering performance.
- Comparison of clustering results on normalized vs. non-normalized data.

## Datasets

### 1. `iris.csv`
The Iris dataset consists of 149 samples of iris flowers, with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (target label)

### 2. `kmtest.csv`
A custom dataset for clustering analysis, containing two numerical features.

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
