
While solving a problem using Deep Learning, we may come up with different types of tasks:

Binary Classification : When the target variables has only two classes.
Activation function in final layer : sigmoid

Multi-Class Classification : Where there are multiple classes in the target class.
Activation function in final layer : softmax

Multi-Label Classification: Multi-label classification involves predicting zero or more class labels from the input data.
The MLP model will foresee the likelihood for each class label. This implies it will foresee three probabilities for each example.
These can be changed over to crisp class labels by rounding the probabilities to 0.0 or 1.0. 
Since we need to determine whether something is present/occurred or not, we can only assign it either 0 or 1 in prediction. 
Hence our output layer has to have sigmoid activation function to predict either 0 or 1 for different output neurons. 
Sigmoid converts each score of the final node between 0 to 1 independent of what the other scores are. 
Activation function in final layer : sigmoid


Regression with one output:
Activation function in final layer : Linear


Regression with multiple outputs:
Activation function in final layer : Linear

<img width="695" alt="image" src="https://user-images.githubusercontent.com/31846843/172292566-150b0c2a-ef9c-4136-9579-23f39f8f65c2.png">

