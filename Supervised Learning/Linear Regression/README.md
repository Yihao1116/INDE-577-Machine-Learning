
# Linear Regression for Diabetes Progression Prediction

## Outline

1. **Introduction**
2. **Data Loading and Preprocessing**
   - Diabetes Dataset from Sklearn
   - Data Conversion to DataFrame
3. **Linear Regression Implementation**
   - Coefficient Computation Function
   - Training and Test Split
   - Model Evaluation
4. **Prediction and Visualization**
   - Scatter Plot of True vs Predicted Values
   - Regression Metrics: R-squared and MSE
5. **Conclusion**

## Data Description

In this analysis, we employ the Diabetes dataset provided by the `sklearn.datasets` library. The goal is to predict the progression of diabetes based on various diagnostic measurements. 

## Linear Regression Implementation

We forgo the use of the conventional `LinearRegression` model from `scikit-learn` and instead implement the linear regression using the normal equation. The coefficients are calculated using the formula \(eta = (X^TX)^{-1}X^TY\). We split the dataset into a training set and a testing set to evaluate the performance of our model.
