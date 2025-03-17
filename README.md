# DL-Assignment_1
NA21B075
Link to Wandb Report: [https://wandb.ai/na21b075-indian-institute-of-technology-madras/wandb/reports/DA6401-Assignment-1--VmlldzoxMTcxODcwNg/edit?draftId=VmlldzoxMTgzNTk5MA==](https://wandb.ai/na21b075-indian-institute-of-technology-madras/wandb/reports/DA6401-Assignment-1--VmlldzoxMTcxODcwNg?accessToken=cdso2ol46qmbx4ur7pnnhugy4a3l9iq94wufa8s9fccm7pdnscqdsgn9ch50jff6)

Link to GitHub : https://github.com/encylope/DL-Assignment_1

**overview**

This repository contains an implementation of a flexible feedforward neural network for classifying images from the Fashion-MNIST dataset. It includes support for multiple hidden layers, various optimization algorithms, hyperparameter tuning with Weights & Biases (wandb), and comparative analysis of loss functions.

**Features**

Flexible Neural Network: Easily configure the number of hidden layers and neurons per layer.

Backpropagation with Multiple Optimizers:Stochastic Gradient Descent (SGD),Momentum-based Gradient Descent,Nesterov Accelerated Gradient Descent,RMSprop,Adam,Nadam

Hyperparameter Tuning with wandb: Uses wandb.sweep to optimize model performance by varying key hyperparameters.

Performance Metrics and Visualization: Validation loss and accuracy tracking, Confusion matrix visualization, Comparison of cross-entropy vs. mean squared error loss


For Questions 1,2,3 and 4, the codes are written separately, with the question put in the text box prior to the code for the question. The plots are present in the report. The function names are pretty self-explanatory, as the purpose served by the function is given as the function name. Logging on to wandb is necessary to generate and see the plots.

Questions 5 and 6 are based on the plots generated in Question 4 and the intuitions drawn from them. The plots and the intuition derived from the plots are given in the report in detail.

The confusion matrix given in Question 7 was generated using wandb only. It is a pretty interactive confusion matrix as it shows the number of examples for each set.

Till now, we had used cross-entropy loss. In Question-8, we used the squared error loss. Even though the accuracies are similar, the values of the loss are drastically different. The plot in the report shows this.

We chose the set of hyperparameters for fashion-MNIST which gave the highest accuracies and used the same on the MNIST dataset. This gave really high accuracies. So, the hyperparameters used for one training set can be very well used for the other training set.

The code is pretty self-explanatory and sequential. Run the cells one after the other to get the desired plots.
