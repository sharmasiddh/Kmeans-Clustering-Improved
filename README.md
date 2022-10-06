# Kmeans-Clustering-Improved


## Below are the Points for Improvement Of KMeans - Algorithm


## Advantages of k-means

### Relatively simple to implement.
### Scales to large data sets.
### Guarantees convergence.
### Can warm-start the positions of centroids.
### Easily adapts to new examples.
### Generalizes to clusters of different shapes and sizes, such as elliptical clusters.


### To be Implemented:

k-Means doesn’t perform well if the clusters have varying sizes, different densities, or non-spherical shapes. -> the Main objective
Has to be run for a certain amount of iteration or it would produce a suboptimal result.
Computationally expensive as distance is to be calculated from each centroid to all data points.
Can’t handle high dimensional data -> Using Lable Encoder we can convert the High Dimensional Dataset to numerical( this comes under - Data Prepocessing ) - so that after complexity will reduce
Number of clusters need to be specified -> using ELbow method we can get the - specific number


Not getting the solutions for below problem statement:

{
	Since initial centroids are arbitrarily chosen, the result is not exactly replicable.
	Shows out of memory error for large datasets

}
