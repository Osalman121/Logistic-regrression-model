Logistic Regression with Regularization and Gradient Descent

This project implements logistic regression with regularization using gradient descent for binary classification. 
The project demonstrates the following concepts:

Logistic regression and its implementation.
Regularization (L2 regularization) to prevent overfitting.
Gradient descent optimization algorithm.
Using decision boundaries to classify data points.
Evaluating the model's accuracy.
Table of Contents
Data Description
Installation
Usage
Project Structure
Functions Overview
Results and Observations
Data Description

The project uses two datasets:

ex2data1.txt: This dataset contains two features (Exam 1 score and Exam 2 score) and a binary label indicating whether a student was admitted to a university (1) or not (0).
ex2data2.txt: This dataset contains two features (Microchip Test 1 and Microchip Test 2) and a binary label indicating whether a microchip was accepted (1) or rejected (0).
Installation



sigmoid: Computes the sigmoid function of the input.
compute_cost: Computes the cost of logistic regression.
compute_gradient: Computes the gradient of the cost function.
compute_cost_reg: Computes the cost of logistic regression with regularization.
compute_gradient_reg: Computes the gradient of the cost function with regularization.
gradient_descent: Implements gradient descent optimization.
predict: Predicts the output label (0 or 1) for given inputs.
Results and Observations
The project demonstrates how logistic regression can be used for binary classification.
Regularization is used to control the complexity of the model and prevent overfitting.
The code includes visualizations that help understand the decision boundary and the data points.
The accuracy of the model can be computed and printed for evaluation.

Credits:
This code is adapted from educational material from OpenAI and other sources for teaching logistic regression concepts and their applications in machine learning.

For any issues or contributions, please feel free to open an issue or create a pull request.
