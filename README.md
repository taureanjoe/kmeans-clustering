# K-Means Clustering
![fifa2022](https://storage.googleapis.com/kaggle-datasets-images/1617785/2659800/c06a7a3de61a874af446f350118ca9ca/dataset-cover.jpg?t=2021-09-28-18-06-09](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2zUwMjiFPiR7HB_sqF9P7EnFIFiffr5UL0etXQynQidofdhJaAOibE8u_-bFX7Z4dVuk&usqp=CAU))
Building a K-means clustering algorithm from scratch and using it to cluster the FIFA22 data.

Clustering is an unsupervised machine learning technique that can find patterns in your data. K-means is one of the most popular forms of clustering.

We'll create our algorithm using python and pandas. We'll then compare it to the reference implementation from scikit-learn.

Project Steps

* Write out pseudocode for the algorithm
* Code the k-means algorithm
* Plot the clusters from the algorithm
* Compare performance to the scikit-learn algorithm

## K-means overview

K-means is an unsupervised machine learning technique that allow us to cluster data points. This enables us to find patterns in the data that can help us analyze it more effectively. K-means is an iterative algorithm, which means that it will converge to the optimal clustering over time.

To run a k-means clustering:

* Specify the number of clusters you want (usually referred to as `k`).
* Randomly initialize the centroid for each cluster. The centroid is the data point that is in the center of the cluster.
* Determine which data points belong to which cluster by finding the closest `centroid` to each data point.
* Update the centroids based on the geometric mean of all the data points in the cluster.
* Run 3 and 4 until the `centroids` stop changing. Each run is referred to as an iteration.

# Code

You can find the code for this project [here](https://github.com/taureanjoe/kmeans-clustering).

## Data

We'll be using data from FIFA, which you can download [here](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset?select=players_22.csv). We'll use the file `players_22.csv`.
