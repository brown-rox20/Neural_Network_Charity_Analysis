# Neural_Network_Charity_Analysis

## Background

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

## Results

Some of the advantages follow:

- There is a distributed effort to find optimal weights—faster.
- Each neuron can focus on different features to identify nonlinear effects—smarter.
- It is less likely to fixate on complex variables—more robust. I will add a third hidden layer (making this a deep learning netowrk)

It is important to use an activation function that matches the complexity of the input data. If we wanted to rank the four most-used activation functions by data complexity and ideal use case, the order would be as follows:

- The sigmoid function values are normalized to a probability between 0 and 1, which is ideal for binary classification (like our output layer).
- The tanh function can be used for classification or regression, and it expands the range between -1 and 1 (this is the range of our scaled data).
- The ReLU function is ideal for looking at positive nonlinear input data for classification or regression.
- The Leaky ReLU function is a good alternative for nonlinear input data with many negative inputs.

## Summary

A two-layer Neural Network Model will predict results with 72% accuracy. The combination of several optimization techniques improved the accuracy slightly, but are met with diminishing returns for the additional effort. To improved accuracy, it is suggested to explore other machine learning methods such as Logistic regression, RandomForestClassifier, or Support-vector machine.
