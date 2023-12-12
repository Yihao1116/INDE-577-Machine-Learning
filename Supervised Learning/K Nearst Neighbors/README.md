
# README

## Outline
1. Introduction
2. Data Loading and Preprocessing
   - Wine Dataset
   - Song Popularity Dataset
3. K Nearest Neighbors Classifier
   - Model Definition
   - Distance Function
   - KNN Function
   - Prediction Function
   - Error Calculation
4. Model Evaluation
   - Error Rate Visualization
5. Song Recommendations
   - Recommendations Function
   - Example Usage
6. Conclusion

## Data Description
The notebook utilizes two datasets: the `wine` dataset from `sklearn.datasets` for classification purposes, and the `Song Popularity Dataset` obtained from Kaggle for recommendations. The `wine` dataset includes chemical measurements from wine samples, while the song dataset contains various features related to song characteristics and popularity.

## K Nearest Neighbors Implementation
The KNN model is implemented from scratch, defining a distance function to compute the similarity between data points, and a KNN function to identify the nearest neighbors based on the distance. The model is tested on the wine dataset for classification accuracy and visualizes the error rate against different k values.
