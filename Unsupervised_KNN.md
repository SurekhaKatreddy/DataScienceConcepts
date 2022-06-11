KNN is an Unsupervised approach most commonly used and one of the simplest algorithms for pattern identification in classification and regression.
The algorithm aims at identifying K nearest neighbors for each of the data points so as to identify similarities in the data.

# Euclidean distance 
<img width="375" alt="image" src="https://user-images.githubusercontent.com/31846843/173194040-5741bc52-dd98-41cf-aade-e9085bdf3ca7.png">

Approach:
1. Identify the similar items based on Euclidean distance
2. Add the identified items to sorted data collection
3. Pick the first K entries from the sorted collection as the nearest neighbours.

# Finding optimal value for K
the smaller the K— the lesser the number of points utilised to create a prediction. This results in over-fitting.

# Points to remember
* The data needs to be scaled so as to avoid the dominance of large distance over the smaller ones.
* Prone to overfitting when there is a noise in the data
* Time consuming for large datasets.
* KNN is suited for lower dimensional data
