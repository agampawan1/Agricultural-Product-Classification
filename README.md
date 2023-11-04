# Agricultural-Product-Classification
Machine learning project to classify agricultural products based on dimensional and shape factors. Dive into the world of agricultural data analysis and prediction

# Predicting Agricultural Product Class

![Cover-23-AI-in-agriculture](https://github.com/agampawan1/Agricultural-Product-Classification/assets/120245764/3f1dd7a8-c6f3-4548-aab2-fc7a95b321f8)



## Overview
In this project, we aim to classify agricultural products based on various dimensional and shape factors. We explore a dataset with the following characteristics:

- Number of Entries: 13,611
- Number of Columns: 17
- Data Types: 14 float64, 2 int64, 1 object

We perform data preprocessing, and visualization, and employ three machine-learning models to classify agricultural products. Here's a brief overview of the project:

## Dataset
We work with a dataset containing information about agricultural plants, including factors like area, perimeter, major axis length, and shape factors. The dataset contains no missing values and 68 duplicates, which are removed during preprocessing. We also encode the categorical 'Class' column and perform various visualizations.

## Data Visualization
We visualize the data using techniques like pair plots, histograms, distribution plots, and scatter plots to gain insights into the relationships between features and the target variable.

## Machine Learning Models
We employ three machine-learning models:

1. **Random Forest Classifier**: Achieving an accuracy of 91.47%, with precision, recall, and F1-score results.
2. **K-Nearest Neighbors (KNN)**: Achieving an accuracy of 91.95%, with precision, recall, and F1-score results.
3. **Support Vector Classifier (SVC)**: Achieving an accuracy of 87.93%, with precision, recall, and F1-score results.

## Model Comparison
Comparing the three models, K-Nearest Neighbors (KNN) outperforms the others, demonstrating the highest accuracy, precision, recall, and F1-score. It is the most suitable model for classifying agricultural products based on the provided data.

## Conclusion
This project showcases the process of classifying agricultural products based on dimensional and shape factors using machine learning. The K-Nearest Neighbors model is the best-performing among the models considered.

Feel free to explore the code, visualizations, and results in this repository to learn more about this agricultural product classification project.

