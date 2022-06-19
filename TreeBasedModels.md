# Tree based models
 In tree based models, the internal node of the tree represents an attribute and each leaf node denotes a class label.
 
# Split criteria : Information gain

What is entrophy?
Measure of randomness of data - works only with the categorical target values. 
Lesser the entropy higher the information gain, which will lead to more homogeneous or pure nodes.

 <img width="694" alt="image" src="https://user-images.githubusercontent.com/31846843/174466284-88c9f301-81cc-4f9b-aa02-8ed5b64f52b9.png">

 Information Gain = 1 - Entrophy
 
# Advantages of tree based models
  1. Unimpacted by skewness in the data.
  2. Less effort preprocessing data - no scaling / normalization is required.
  3. Can be used to solve both regression and classification problems.
  Ex: Decision tree, Random Forest, 

# Disadvantages of tree based models
 1. Higher training time particularly for regression.
 2. Slight changes in data might cause drastic time in models. 

# Bagging (Bootstrap aggregating)
  An ensembling technique wherein a forest of decision trees are constructed and the average of the results is considered for 
  a generalized result.
  
# Boosting 
  Boosting can have higher accuracy because each base model/estimator gets to learn from the previous model mistakes. 
  Adaptive Boosting - learning from the mistakes of the previous model by assigning higher weightage to misclassified instances.
  Gradient boosting - creates a series of models to lower the residual errors gradually.
  Extreme Gradient Boosting - 
