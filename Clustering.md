Given the data of independent features without any target or dependant variable, clustering is an unsupervised machine learning technique
that aims to find the similarity of the data points.

It could be similarity ranging from
Customer buying similar items based on their purchase history used in Customer Segmentation
Users clicking like on same posts in social media
Stocks with similar trends or metrics.

Identyfing the buying patterns of the customer is in trend as businesses tries to identify group their customers based on the past trends
in the data so as to identify the customers who might possibly churn and try to retain them may be by running targetted promotions or 
add campaigns or so on.

# what is simialrity based on?
  Distance
  
# Types of clustering : hard vs soft
  Hard clustering is about grouping the data items such that each item is only assigned to one cluster. ex: KMeans
  Soft clustering is about grouping the data items such that each item may be part of more than one cluster. ex: GMM, Fuzzy C-means 
  For soft clustering algorithms, we need to compute a fuzziness coefficient that controls the degree of fuzziness.


# Popular clustering techniques
  KMeans - based on distance - calculates random centroids and assigns data points to closest centroids. Recalculates centroids and reassigns 
  the data points. Repeats the process until the centroids no longer change. Guarantees convergence. A value of K should be provided in advance.
  Optimal value of K can be found using Elbow method -or Shilloute score
  
  DBScan - Density-based spatial clustering of applications with noise (DBSCAN) - robust to outliers. 
  This is a clustering method that is used in machine learning to separate clusters of high density from clusters of low density.
  Epsilon(eps) i.e the minimum distance between the points to consider them as part of seperate groups. Smaller the value, data points are not 
  clustered and treated as data points in the same cluster. minPoints ≥ D + 1.
  
  Hierarchial - Hierarchical clustering, also known as hierarchical cluster analysis, is an algorithm that groups similar objects into 
  groups called clusters. The endpoint is a set of clusters, where each cluster is distinct from each other cluster, and the objects within 
  each cluster are broadly similar to each other.
  Hierarchical clustering is one of the popular and easy to understand clustering technique. This clustering technique is divided into two types:
  a. Agglomerative - bottom up approach in which each data point is considered as an individual cluster and clusters are formed by grouping
     similar items into groups.
  b. Divisive - top down approach of divinding single cluster into groups.

  The Hierarchical clustering Technique can be visualized using a Dendrogram.
  A Dendrogram is a tree-like diagram that records the sequences of merges or splits.
  
  <img width="513" alt="image" src="https://user-images.githubusercontent.com/31846843/172530320-d657e10a-49f1-4f42-b091-d07605de924c.png">

  
  
