# ML_DS_Concepts_Codes
# Explanation and implementation of Machine Learning Algorithms in Data Science

# K-Means Clustering
### Introduction 
K-Means is an unsupervised machine learning algorithm where the goal is to determine the inherent patterns in the given unlabeled data i.e. find out if the data can be divided into groups or clusters which share similar characteristics. It is a very powerful technique and is widely used for data mining. 
### Description
The K-Means clustering algorithm can be summarized in two main steps which get executed iteratively for a given data set with a pre-determined number of clusters as described below:
1. Cluster assignment: In this step each data point gets assigned to a cluster depending on which cluster it is closest to. It therefore involves computing the distance of the given data point w.r.t each cluster. The cluster for which the distance comes out minimum is the cluster which gets assigned to the data point. 
2. Cluster centroid update: Once the data points gets assigned to their respective clusters, this steps inolves updating the cluster centroid based on the data points which are associated with it. The cluster centroid is updated based on the mean value of the location of all points in that cluster. 
![Clustering_Example](https://user-images.githubusercontent.com/28870788/130859728-4b159a57-c614-4f7a-80a2-4d4afc201660.png)
