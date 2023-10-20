# Model-Selection
This repository contains Python code for implementing Bayesian linear regression experiments with the tasks outlined below. The code not use special libraries or modules other than standard I/O, math, and plotting libraries.

Task 1: Regularization
The goal of this task is to explore the role of regularization in linear regression and investigate the impact of regularization parameters on model performance. The code provided performs regularized linear regression for four datasets and plots the training set MSE and test set MSE as functions of the regularization parameter lambda. The results are compared to the MSE of the true functions given in the assignment.

Task 2: Model Selection using Cross Validation
In this task, the code implements 10-fold cross-validation on the training set to select the optimal value of lambda. It then retrains the model on the entire training set with the selected lambda value and evaluates the performance on the test set.
