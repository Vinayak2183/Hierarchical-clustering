# Hierarchical Clustering for Customer Segmentation

This repository contains a Jupyter notebook that demonstrates hierarchical clustering for customer segmentation using the Mall Customers dataset.

## Overview

The project applies hierarchical clustering to segment mall customers based on their annual income and spending score. The notebook covers:

1. Data loading and preprocessing
2. Using dendrograms to determine optimal clusters
3. Implementing Agglomerative Clustering
4. Visualizing the resulting clusters

## Dataset

The dataset used is `Mall_Customers.csv`, which contains customer information including:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

The analysis focuses on Annual Income and Spending Score for clustering.

## Dependencies

The notebook requires the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- SciPy

## Usage

1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook `hierarchical_clustering.ipynb`

## Key Steps

1. **Data Preparation**: 
   - Import necessary libraries
   - Load and preprocess the dataset
   - Extract relevant features (Annual Income and Spending Score)

2. **Dendrogram Analysis**:
   - Plot dendrogram to determine optimal number of clusters
   - Use Ward's method for linkage

3. **Model Training**:
   - Apply Agglomerative Clustering with 5 clusters
   - Fit the model to the data

4. **Visualization**:
   - Plot the clusters to visualize customer segments

## Results

The hierarchical clustering analysis identifies distinct customer segments based on spending behavior and income levels, which can be valuable for targeted marketing strategies.
