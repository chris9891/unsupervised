# unsupervised
Description of KMeans Clustering: KMeans is an iterative algorithm that partitions the dataset into K distinct clusters. The algorithm works by:

Randomly initializing K centroids (mean points of clusters).
Assigning each data point to the nearest centroid based on Euclidean distance.
Recomputing the centroids based on the new cluster assignments.
Repeating steps 2 and 3 until the centroids stabilize (no change in assignments).
Why KMeans is suitable for the Iris dataset: The Iris dataset is relatively small and contains continuous features, making KMeans a good fit as it efficiently clusters data with similar characteristics.

Apply KMeans Clustering: We'll set n_clusters=3 because we know the Iris dataset has three species.

 Hierarchical Clustering:
Description of Hierarchical Clustering: Hierarchical clustering builds a hierarchy of clusters by either:

Agglomerative (bottom-up): Each data point starts in its own cluster, and pairs of clusters are merged step by step based on their similarity.
Divisive (top-down): All data points start in one cluster, and splits are made recursively until each point is its own cluster.
The result is a dendrogram, which visually represents the process of clustering.

Why Hierarchical clustering is suitable for the Iris dataset: Hierarchical clustering works well for small datasets, as it provides a detailed structure of clusters. Since Iris has a manageable size, hierarchical methods are computationally feasible and can reveal different levels of relationships between points.

Apply Hierarchical Clustering: We’ll use Agglomerative clustering with n_clusters=3.
