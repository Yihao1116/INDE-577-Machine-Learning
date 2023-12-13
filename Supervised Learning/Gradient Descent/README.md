
# README

## Outline

1. Introduction
2. Data Preparation
   - California Housing Dataset
   - Feature Standardization
   - Train-Test Split
3. Gradient Descent Optimization
   - Weight Initialization
   - Batch Gradient Descent Algorithm
   - Cost Function Equation
   - Learning Rate and Iterations
4. Model Evaluation
   - Mean Squared Error (MSE)
   - R² Score
   - Prediction vs Actual Comparison
5. Conclusion

## Data Description

The notebook utilizes the `california_housing` dataset from `sklearn.datasets`, which comprises various housing-related features to predict the median house values in California districts. The dataset is randomly split into training and testing sets, with 80% of the data allocated for training and 20% for testing.

## Gradient Descent Equations

The Gradient Descent algorithm iteratively updates the weights to minimize the cost function. The update rule for the weights with a learning rate \\( \\alpha \\) and for \\( m \\) training examples is given by:

$ \\theta := \\theta - \\left( \\frac{\\alpha}{m} \\right) \\times (X^T \\times (\\text{prediction} - \\text{actual})) \\$

The cost function representing the Mean Squared Error is:

$ \\text{cost} = \\frac{1}{2m} \\sum(\\text{prediction} - \\text{actual})^2 \\$

where $( \\text{prediction} \\)$ is the dot product of $( X \\) and \\( \\theta \\)$.
