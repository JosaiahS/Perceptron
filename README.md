# Rosenblatt's Perceptron for binary classification

This repository is for the educational purpose of implementeting Rosenblatt's Perceptron.

## Overview of Algorithm
Rosenblatt's Perceptron is a supervised learning algorithm primarly used for binary, linearly separable classification. Frank Rosenblatt published the earliest concept of the a Perceptron Learning rule in 1957, giving us a simplified representation of how a single neuron int he brain works. This algorithm can be used to predict if an new data point belonged in one class or the other. 

## Iris Dataset
The dataset that will be used in this implementation is the Iris dataset which contains measurements for 150 iris flowers for three species: Setosa, Versicolor, and Virginica. Each flower has information regarding their sepal length, sepal width, petal length, and petal width. 
## Algorithm Explanation
The maing goal of the algorithm is to determine where the decision boundary should be. The decision boundary is the line on the graph that splits the samples into two categories. The algorithm does not know where the correct location for the decision boundary should be without first analyzing a set of examples from the iris dataset. As we go through each example within the set, the algorithm slowly adjusts the location of the decision boundary until there are zero misclassifications. It is only possible to reach zero misclassifications if the data is linearly separable. 



 














