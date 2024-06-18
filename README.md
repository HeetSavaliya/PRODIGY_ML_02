# PRODIGY_ML_01
Prodigy Machine Learning Internship Task 1

Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

Dataset Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

# Summarizing the k-means algorithm

K-means clusters data by iteratively assigning points to the nearest centroid and updating centroids to minimize the within-cluster sum of squares, aiming to partition the data into \( k \) clusters based on Euclidean distance.

# Notebook Summary

## 1. Data Preparation

- using pandas to read csv file and view dataset shape and columns
- create new dataset using relevant features and target variable for the present task

## 2. Data Visualization

- check datatypes in case there is need for encoding categorical values
- check for missing values and duplicate rows
- use violin plots to visualize data for density

## 3. Finding optimum number of clusters

- Use elbow method to find the optimum number of clusters for each group set

## 4. Plotting Clusters using Optimal K

- plot 2D and 3D graphs for K-means clustering and find the different groups of people
