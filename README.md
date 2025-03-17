# DL-Assignment_1
NA21B075
Link to Wandb Report: https://wandb.ai/na21b075-indian-institute-of-technology-madras/wandb/reports/DA6401-Assignment-1--VmlldzoxMTcxODcwNg/edit?draftId=VmlldzoxMTgzNTk5MA==
Link to GitHub : https://github.com/encylope/DL-Assignment_1
Overview

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

Requirements

Python 3.x

TensorFlow / PyTorch

NumPy

Matplotlib

Weights & Biases (wandb)

Install dependencies using:

pip install -r requirements.txt

Usage

1. Train the Model

To train the feedforward neural network, run:

python train.py --epochs 10 --hidden_layers 3 --neurons 64 --batch_size 32 --optimizer adam

2. Run Hyperparameter Sweep

Use wandb to explore different configurations:

wandb sweep sweep_config.yaml
wandb agent <SWEEP_ID>

3. Evaluate the Model

After training, evaluate on the test set:

python evaluate.py --model best_model.pth

4. Generate Confusion Matrix

python plot_confusion_matrix.py --model best_model.pth

Results

Best model accuracy on validation set: XX%

Best model accuracy on test set: XX%

Observations & Insights

The Adam optimizer performed best in terms of convergence speed and accuracy.

Higher weight decay values reduced overfitting but slightly impacted validation accuracy.

ReLU activation provided better gradient flow than sigmoid and tanh.

Models with 4 hidden layers showed a performance improvement over 3-layer models.

Comparison of Loss Functions

We compared cross-entropy loss vs. mean squared error loss. The results showed that cross-entropy loss performed better in classification tasks as it resulted in faster convergence and higher accuracy.

