
# README

## Outline
1. Introduction
2. Data Loading and Preprocessing
   - Iris Dataset
   - Feature Scaling
   - Train-Test Split
3. Neural Network Architecture
   - Activation Functions
   - Loss Function
   - Forward and Backward Propagation
   - Weight and Bias Initialization
   - Training the Neural Network
4. Model Evaluation
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
5. Conclusion

## Data Description
The notebook uses the `iris` dataset from `sklearn.datasets`, which includes four features: sepal length, sepal width, petal length, and petal width, used to classify iris flowers into three species. The data is preprocessed with `StandardScaler` for normalization and split into training and testing sets, with a training set size of 70%.

## Neural Network Implementation
The neural network implemented in this notebook includes two hidden layers and utilizes the sigmoid activation function for the hidden layers and the softmax activation function for the output layer. The cross-entropy loss function is used to compute the error between the predicted probabilities and the actual class labels in one-hot encoded form. The network's weights are updated using the Gradient Descent optimization algorithm through forward and backward propagation steps.
