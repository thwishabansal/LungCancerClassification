# Lung Cancer Risk Prediction
## Introduction
Lung cancer is the leading cause of cancer death worldwide, accounting for 1.59 million deaths in 2018. This project aims to predict the risk of acquiring lung cancer based on various risk factors.

## Dataset
The dataset contains variables such as alcohol level, air pollution level, smoking status (non-smoking or smoking), age, and gender. The goal is to predict whether a data point is at a high, medium, or low risk of acquiring cancer.

## Methodology
### Supervised Learning Models
-  Logistic Regression
- K-Nearest Neighbors (KNN)
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest Classifier

## Results
All models achieved perfect 100% accuracy on both cross-validation and the test set, raising concerns about overfitting. Post-PCA, Random Forest maintained a robust accuracy of 97.50%, showcasing strong generalization with reduced features.
Logistic Regression, KNN, and Decision Tree models exhibited decreased accuracy with PCA, indicating that dimensionality reduction might not be as beneficial for these models. Random Forest emerged as the most robust and generalizable model, maintaining high accuracy even after PCA's feature reduction.

### Unsupervised Learning Model
- K-Means Clustering

## Cluster Analysis
After dropping the target variable (risk level), the dataset was clustered into 5 groups based on their risk factors:
- Cluster 0: Young Adults (Below 30) - Susceptible
- Cluster 1: Forties - Generally Fit
- Cluster 2: Millennials - Fit and Low Susceptibility
- Cluster 3: Forties - Avid Smokers
- Cluster 4: Oldest Age Group - Moderate Susceptibility

## Conclusion
Random forest classification proved to be the best model for the dataset. Clustering the patients into different risk categories based on their risk factors can help in better understanding and profiling different clusters, potentially aiding in early cancer detection and personalized healthcare.




