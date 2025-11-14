# Rosenblatt's Perceptron for binary classification

This repository is for the educational purpose of implementeting Rosenblatt's Perceptron.

## Overview of Algorithm
Rosenblatt's Perceptron is a supervised learning algorithm primarly used for binary, linearly separable classification. Frank Rosenblatt published the earliest concept of the a Perceptron Learning rule in 1957, giving us a simplified representation of how a single neuron int he brain works. This algorithm can be used to predict if an new data point belonged in one class or the other. 

## Iris Dataset
The dataset that will be used in this implementation is the Iris dataset which contains measurements for 150 iris flowers for three species: Setosa, Versicolor, and Virginica. Each flower has information regarding their sepal length, sepal width, petal length, and petal width. 
## Algorithm Explanation
The goal of the perceptron algorithm is to learn a linear decision boundary that separates the training samples into two classes. The algorithm is given labeled examples from the iris dataset and iteratively updates its weight vector as it processess these examples. The weights are adjusted everytime the perceptron misclassifies a sample towards the direction that would move the decision boundary towards correctly classifying that sample. The perceptron theorem guarantees that these updates will eventually produce a decision boundary with zero misclassifications only if the training data are linearly separable. 


 














