# What is classification 
Supervised learning technique to predict categorical data. It can be binary or multi class classification.

# Important metrics: 
  <img width="709" alt="image" src="https://user-images.githubusercontent.com/31846843/173142274-096377f1-be96-4fe6-9721-f3eab04984c1.png">

 Terminology :
 TP = True positive - actual positive cases predicted 
 FN = False Negative - false 
 
1. Sensitivity / TPR (True Positive Rate) / Recall = TP/TP+FN.
   TPR is the probability that an actual positive will test positive. The true negative rate (also called specificity), 
   which is the probability that an actual negative will test negative.
   
2. Specificity / False positive rate (FPR) / Precision = TN/TN+FP.
   It is defined as the probability of falsely rejecting the null hypothesis. It is a measure of accuracy for a test

3. ROC : The Receiver Operator Characteristic (ROC) curve is an evaluation metric for binary classification problems. It is a probability 
   curve that plots the TPR (on y axis) against FPR (on x axis) at various threshold values. 

4. AUC (Area under the curve) - The Area Under the Curve (AUC) is the measure of the ability of a classifier to distinguish between classes 
   and is used as a summary of the ROC curve. The higher the AUC, the better the performance of the model at distinguishing between the 
   positive and negative classes. 

5. Accuracy = (TP + TN) / TP + FP + TN + FN
