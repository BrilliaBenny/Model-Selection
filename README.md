## Model-Selection
This repository contains Python code for implementing Bayesian linear regression experiments with the tasks outlined below. The code not use special libraries or modules other than standard I/O, math, and plotting libraries.

Task 1: Regularization
The goal of this task is to explore the role of regularization in linear regression and investigate the impact of regularization parameters on model performance. The code provided performs regularized linear regression for four datasets and plots the training set MSE and test set MSE as functions of the regularization parameter lambda. The results are compared to the MSE of the true functions given in the assignment.

Task 2: Model Selection using Cross Validation
In this task, the code implements 10-fold cross-validation on the training set to select the optimal value of lambda. It then retrains the model on the entire training set with the selected lambda value and evaluates the performance on the test set.

Task 3: Bayesian Model Selection
This task involves Bayesian linear regression with the utilization of the evidence function for parameter selection. The code initializes alpha and beta, then applies an iterative algorithm to select alpha and beta using the training set. It calculates the mean squared error (MSE) on the test set using the Maximum A Posteriori (MAP) for prediction. The scheme converges within a reasonable number of iterations.

#Prerequisites
Before running the code, make sure you have the following prerequisites installed:

• Python 3.x

• NumPy

• Matplotlib

You can install the required packages using pip:

#Data
There are 4 datasets and each dataset comes in 4 files with the training set in train-name.csv, the corresponding labels (regression values) in trainR-name.csv and similarly for test set. Here I have uploaded all of these datasets in the colab environment one by one. All 4 datasets corresponding to each main dataset have to be in the environment for the code to work.
