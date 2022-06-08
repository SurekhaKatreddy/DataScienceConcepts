
Ensemble modeling is a process where multiple diverse models are created to predict an outcome, either by using many different 
modeling algorithms or using different training data sets i.e Combining several models to make one very reliable model. 
The ensemble model then aggregates the prediction of each base model and results in once final prediction for the unseen data.

# Why Ensembling
There are two main reasons to use an ensemble over a single model, and they are related; they are: 
-- Performance: Ensemble modelling tend to perform better than single model.
-- Robustness: An ensemble reduces the spread or dispersion of the predictions and model performance.

# Promiment ensembling models
 
   <img width="435" alt="image" src="https://user-images.githubusercontent.com/31846843/172523720-fdc30863-9af3-4ec2-b9f1-1327ada752e9.png">

a. Bagging : Also known as Bootstrap aggregating is way to reduce variance in the data by taking in combinations of data from the original source data.
   It is an iterative approach wherein the weight of misclassified instances is increased in the consecutive iteration. Weighted avergae of each of the 
   models is taken as the final prediction. Bagging avoids overfitting of data and is used for both regression and classification models, 
   specifically for decision tree algorithms.
   
   Process explained:
   From N observations each with m features, random samples of subsets of m features are chosen without replacement.
   The feature offering the best split out of the lot is used to split the nodes
   The above steps are repeated n times. It aggregates the output of individual decision trees to give the best prediction

   Bagging algorithms:
   -- Bagging meta-estimator
   -- Random forest, an ensemble of decision trees.

b. Boosting:
   Multiple models are built in sequence unlike the bagging technique. Those data points that are not predicted correctly by the previous
   model are given higher weightage thereby correcting the errors of the previous model. The final model (strong learner) is the weighted 
   mean of all the models (weak learners).
   
   Decision stumps are constructed as opposed to decision trees in the bagging technique. Decision stumps improve upon this by splitting 
   the examples into two subsets based on the value of one feature
   
   In Gradient Boosting, individual models train upon the residuals, the difference between the prediction and the actual results. 
   Instead of aggregating trees, gradient boosted trees learns from errors during each boosting round.
   
   -- AdaBoost
   -- GBM
   -- XGBM
   -- Light GBM
   -- CatBoost
   
   
