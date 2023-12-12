
# Principal Component Analysis (PCA) for California Housing Dataset

## Outline

1. Introduction
2. Data Loading and Standardization
   - California Housing Dataset
3. PCA Implementation
   - Variance Explained Plot
   - Principal Component Scatter Plot
   - Normalized PCA
4. Variance Analysis
   - Cumulative Variance Explained
   - Biplot Representation
   - 3D PCA Visualization
5. Conclusion

## Data Description

The notebook utilizes the California Housing dataset available from `sklearn.datasets`. This dataset contains metrics such as median income, housing average age, average rooms, average bedrooms, population, and average occupancy.

## PCA Implementation

Principal Component Analysis is conducted to reduce the dimensionality of the dataset, both on raw and normalized data. The normalization process scales the data to a standard normal distribution, which is crucial when features have different units and scales.

## Visualization

The PCA results are visualized through several plots that display the variance explained by each principal component, as well as the data projected onto the first two principal components. These visualizations help in understanding the data's structure in the reduced dimensions.
