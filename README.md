# Exploring-Neural-Networks-with-QMNIST-Performance-Tuning-and-Hyperparameter-Optimization

Project Overview
This project explores building, modifying, and tuning a neural network using the QMNIST dataset, focusing on understanding model performance in terms of accuracy and the impact of different hyperparameters. The goal is to start with a baseline model and gradually implement modifications such as adding dense layers, increasing node counts, and experimenting with optimizers and loss functions. Finally, we take a deeper dive into the backpropagation process by manually calculating derivatives for a small network.

Key Steps:
Baseline Model Setup:

Using PyTorch, we reproduced a neural network model trained on the QMNIST dataset to classify handwritten digits.
Achieved baseline accuracy on both the training and test datasets.
Performance Modification:

Chose one of the following modifications:
Added another Dense layer with 128 nodes.
Increased the number of nodes in an existing layer to 256.
Hypothesized how this change would impact performance and trained the modified model.
Model Performance Reporting:

Reported on the accuracy of the modified model and whether it aligned with the initial hypothesis.
Hyperparameter Tuning:

Experimented with various optimizers (Adam, SGD, etc.), loss functions (CrossEntropy, MSE, etc.), activation functions (ReLU, Sigmoid), and dropout rates to improve performance.
Documented the impact of these changes on the model's performance.
Manual Backpropagation Example:

Performed one round of forward and backward steps for a smaller network by manually calculating derivatives, demonstrating the backpropagation process without relying on automatic differentiation.
Reference video: Backpropagation Explained
Results:
Baseline model performance: Accuracy on train/test data.
Modified model performance: Accuracy after adding layers and changing node counts.
Impact of different hyperparameters: Detailed comparison of model accuracy with different optimizers, loss functions, and activation functions.
