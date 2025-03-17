# DL-Assignment_1
NA21B075
Link to Wandb Report: https://wandb.ai/na21b075-indian-institute-of-technology-madras/wandb/reports/DA6401-Assignment-1--VmlldzoxMTcxODcwNg/edit?draftId=VmlldzoxMTgzNTk5MA==
Link to GitHub : https://github.com/encylope/DL-Assignment_1
#overview

This repository contains an implementation of a flexible feedforward neural network for classifying images from the Fashion-MNIST dataset. It includes support for multiple hidden layers, various optimization algorithms, hyperparameter tuning with Weights & Biases (wandb), and comparative analysis of loss functions.

Features
Flexible Neural Network: Easily configure the number of hidden layers and neurons per layer.

Backpropagation with Multiple Optimizers:

Stochastic Gradient Descent (SGD)

Momentum-based Gradient Descent

Nesterov Accelerated Gradient Descent

RMSprop

Adam

Nadam

Hyperparameter Tuning with wandb: Uses wandb.sweep to optimize model performance by varying key hyperparameters.

Performance Metrics and Visualization:

Validation loss and accuracy tracking

Confusion matrix visualization

Comparison of cross-entropy vs. mean squared error loss

