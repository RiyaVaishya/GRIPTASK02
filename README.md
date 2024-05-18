# Task-02

# Iris Dataset Clustering

This project aims to determine the optimal number of clusters in the Iris dataset and represent them visually using Jupyter Notebook with Python.

## Overview:-

The Iris dataset is a well-known dataset in the field of machine learning. It contains measurements of four features (sepal length, sepal width, petal length, and petal width) for three species of iris flowers (setosa, versicolor, and virginica). The goal of this project is to use the K-means clustering algorithm to predict the optimum number of clusters and visualize the results.

## Dataset:-

The dataset used in this project is the Iris dataset, which contains the following columns:

- `Id`: An identifier for each sample.
- `SepalLengthCm`: Sepal length in centimeters.
- `SepalWidthCm`: Sepal width in centimeters.
- `PetalLengthCm`: Petal length in centimeters.
- `PetalWidthCm`: Petal width in centimeters.
- `Species`: The species of the iris flower.

## Steps Performed:-

1. **Load the Dataset**: Read the dataset from a CSV file using Pandas.
2. **Data Preprocessing**: Extract relevant features for clustering.
3. **Standardize the Features**: Scale the features to have zero mean and unit variance.
4. **Determine the Optimal Number of Clusters**: Use the Elbow Method to find the optimal number of clusters by calculating the Within-Cluster Sum of Squares (WCSS).
5. **Silhouette Analysis**: Evaluate the quality of clusters using the silhouette score and silhouette plot.
6. **K-means Clustering**: Apply the K-means algorithm with the optimal number of clusters.
7. **Visualize the Clusters**: Create visualizations to represent the clusters.

## Visualizations:-

### Elbow Method-

The Elbow Method helps determine the optimal number of clusters by plotting the WCSS against the number of clusters.

### Silhouette Analysis-

The silhouette analysis helps determine the quality of clusters.

### Pairplot of Features with Clusters-

A pairplot of the features colored by cluster.

## Requirements:-

Python 3.x

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

## Conclusion:-

In this project, we applied the K-means clustering algorithm to the Iris dataset to uncover underlying patterns in the sepal and petal measurements of iris flowers. Through careful analysis and visualization, we determined the optimal number of clusters and successfully grouped the iris flowers into distinct clusters.

Our findings demonstrate the effectiveness of clustering techniques in identifying natural groupings within datasets. By understanding the inherent structure of the data, we gain valuable insights that can inform decision-making and further analysis.

Overall, this project highlights the importance of exploratory data analysis and clustering techniques in extracting meaningful information from datasets and uncovering hidden patterns.

## My Linkedin profile:- www.linkedin.com/in/riya-vaishya-537731278
