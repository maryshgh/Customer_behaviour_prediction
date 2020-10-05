# Customer_behaviour_prediction
This is a code package related to the following project. In this project, the goal is to predict the bank customer decision on continuing using of the bank service or exiting. The following features are used for prediction: credit score, geography, gender, age, tenure, balance, number of products, having bank's credit card, being an active member, and estimated salary. A deep neural network has used for predicting the customer's decision on staying or leaving the bank. The network has an input layer of size of 12 (because we consider 10 features, one is categorical and preprocessed using OneHotEncoder, hence two additional columns has been added), 2 hidden layer with 6 neurons in each layer and Relu activation function, and output layer with just one neuron and Sigmoid activation function. The sigmoid function is used for the output layer because the desired outputs are {0,1}, and this is actually is a classification problem. Furthermore, for training, the 'adam' optimizer has been used which minimizes the loss which is binary cross entropy for this binary classification problem.

This repository contains the Python code required to reproduces all the numerical results.

## Content of Code Package
The package contains one Python file including Python code and one comma seperated file including 10000 samples.

