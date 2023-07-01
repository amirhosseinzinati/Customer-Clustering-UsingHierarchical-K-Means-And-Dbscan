# Customer Clustering using Hierarchical Clustering, K-means, and DBSCAN
This project aims to cluster customers of a mall based on their basic information such as ID, age, gender, income, and spending score. The clustering is done using Hierarchical Clustering, K-means, and DBSCAN algorithms.

# Dataset
The dataset used for this project contains the basic information of customers of a mall. It includes the following features:

ID: Customer ID

Age: Customer age

Gender: Customer gender

Income: Customer income

Spending Score: Score assigned by the mall based on customer behavior and spending nature

You can download Dataset form [this link](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
# Algorithms used
The following clustering algorithms are used in this project:

## Hierarchical Clustering
Hierarchical Clustering is a bottom-up clustering approach that starts by assigning each data point to its own cluster and then merging them based on similarity until all data points belong to a single cluster.

## K-means Clustering
K-means is a centroid-based clustering algorithm that partitions the data into k clusters. It starts by randomly selecting k centroids and then assigns each data point to the closest centroid. The centroids are then updated based on the mean of the data points in each cluster, and the process is repeated until convergence.

## DBSCAN Clustering
DBSCAN is a density-based clustering algorithm that groups together points that are close to each other and have a high density of neighbors. It starts by selecting a random point and then expands the cluster by adding neighboring points until no more points can be added. Points that cannot be added to any cluster are considered noise.

# Results
The results of the clustering algorithms are plotted using scatterplots. Each plot shows the clustered data points with different colors representing different clusters. The plots can help to identify patterns and insights from the clustering results.
