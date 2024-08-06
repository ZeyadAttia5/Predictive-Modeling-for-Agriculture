# Soil Metrics and Crop Prediction

## Project Overview

Developed a multi-class classification model to predict the optimal crop based on soil metrics. The dataset contains various measures of soil quality, and the objective is to determine which crop would yield the best results based on these measures.

## Key Steps

### Data Exploration and Visualization

- Explored the dataset to understand distributions and correlations between soil metrics.
- Visualized soil metric distributions and crop frequencies to identify trends and anomalies.

### Data Preprocessing

- Checked for missing values and handled any detected issues.
- Split the data into training and testing sets to evaluate model performance.
- Processed the data to ensure it was suitable for model training.

### Feature Importance Analysis

- Trained a Logistic Regression model for each soil metric (`N`, `P`, `K`, `pH`).
- Evaluated the performance of each feature using the F1 score to determine which feature provides the best predictive value.
- Identified the single most important feature for predictive performance.

### Model Training and Evaluation

- Used Logistic Regression to evaluate the predictive power of individual features.
- Calculated F1 scores to assess model performance for each feature.
- Compared feature performances to identify the most impactful soil metric.

## Summary

This project successfully developed a classification model to predict the best crop for a given field based on soil metrics. By evaluating the importance of different soil features, the model identifies the key metric that most significantly influences crop selection, providing valuable insights for optimizing crop yields.
