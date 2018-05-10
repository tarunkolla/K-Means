# K-Means



#### Data Set:

[breast-cancer-wisconsin.data](http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/) or you can go
to find it on GitHub [here](https://github.com/tarunkolla/K-Means/blob/master/data.txt)

The data set contains 11 columns, separated by comma. The first column is the example id, and has been ignored. The second to tenth columns are the 9 features, based on which K-means algorithm works. The last column is the class label, and has been ignored as well.

#### Implementation:

K-Means algorithm performs clustering on the above dataset with K = 2, 3, 4, 5, 6, 7, 8. For each K value, the algorithm is first run and then the potential function is computed as follows:

![Potential Function](https://github.com/tarunkolla/K-Means/blob/master/Read-Me-Doc/Potential%20Function.png)

where m is the number of examples, xj denotes the feature vector for j th example and µC(j) refers to the centroid of the cluster that xj belongs to.

Empty clusters in a certain iteration have been droped and randomly the largest cluster is split into two clusters to maintain the total number of clusters at K.

#### Results:

A graph is plot for the values of k and L(K).

![Graph](https://github.com/tarunkolla/K-Means/blob/master/Read-Me-Doc/Graph.png "graph ploted with ptoential function for different values of k")
