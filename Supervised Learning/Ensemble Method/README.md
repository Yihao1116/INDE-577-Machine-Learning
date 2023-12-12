
# README

## Outline
1. Introduction
2. Data Loading and Preprocessing
   - Breast Cancer Wisconsin Dataset
   - Dimensionality Reduction with PCA
3. Ensemble Methods Classifier
   - Model Definition and Initialization
   - Training Ensemble Models
   - Model Evaluation
4. Decision Boundary Visualization
5. Feature Importance Analysis
6. Conclusion

## Data Description
This notebook employs the Breast Cancer Wisconsin (Diagnostic) dataset from `sklearn.datasets` for binary classification between malignant and benign tumor classes. Principal Component Analysis (PCA) is applied to the dataset to reduce its dimensionality for visualization purposes.

## Ensemble Methods Implementation
The ensemble methods involve combining different machine learning classifiers to improve prediction performance. The ensemble includes a Logistic Regression, a Random Forest, and a Support Vector Machine with a hard voting mechanism. Additionally, a bagging classifier with decision stumps is implemented. All models are trained on the PCA-reduced feature set.
