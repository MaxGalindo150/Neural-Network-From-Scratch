# Neural-Network-From-Scratch

This repository contains code for implementing a neural network from scratch using numpy. The notebook demonstrates the step-by-step process of creating a neural network, training it, and evaluating its performance on a binary classification problem.

## Contents
1. [Data Preparation](#data-preparation)
2. [Activation and Loss Functions](#activation-and-loss-functions)
3. [Neural Network Construction](#neural-network-construction)
4. [Training the Model](#training-the-model)
5. [Analysis](#analysis)

## Data Preparation
The notebook starts by generating a synthetic dataset consisting of 10,000 samples with two features. It visualizes the data on a scatter plot, where each class is represented by a different color.

## Activation and Loss Functions
The notebook defines the sigmoid and ReLU activation functions, which are used in the hidden layers of the neural network. The Mean Squared Error (MSE) loss function is also implemented for training the network.

## Neural Network Construction
The notebook provides a function to initialize the parameters of the neural network based on the specified layer dimensions. It demonstrates an example network structure with an input layer, two hidden layers, and an output layer.

## Training the Model
The notebook includes a training function that performs forward propagation, backpropagation, and gradient descent to update the weights and biases of the network. It iteratively trains the network on the provided dataset and tracks the training errors.

## Analysis
The notebook analyzes the performance of the trained neural network by plotting the training errors over iterations. It also generates new, unclassified data and uses the trained network to classify it. The final classification results are visualized on a scatter plot.

The "Neural-Network-From-Scratch" repository provides a comprehensive example of implementing a neural network using numpy and demonstrates its effectiveness in solving a binary classification problem.
