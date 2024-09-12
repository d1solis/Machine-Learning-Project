# Machine-Learning-Project

## Overview
This project analyzes three different datasets: Car Evaluation, Iris, and Zoo. The analysis is performed using various data science techniques and visualizations. The primary goal is to explore various classification algorithms, handle different data types, and evaluate model performance across diverse datasets.

## Datasets
1. Car Evaluation: Consists of categorical features that evaluate cars based on several criteria, aiming to classify car acceptability. 
2. Iris: A well-known dataset that contains numerical features describing iris flowers, with the goal of classifying them into three species.
3. Zoo: Contains binary and categorical features describing various animals, with the goal of predicting the class to which each animal belongs to.

## Features
### Data Preprocessing:
- Ordinal Encoding for binary features (e.g., "hair", "feathers" in the zoo dataset) to represent true/false values.
- One-Hot Encoding for multi-class categorical features (e.g., "legs" in the zoo dataset). Handling numerical features in the Iris dataset.
  
### Data Cleaning: 
- Removal of missing or inconsistent data to ensure accurate analysis.

### Class Imbalance Handling:
- Applied SMOTE (Synthetic Minority Over-sampling Technique) to address imbalanced classes in the zoo dataset.

### Classification Models:
- Used Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree classifiers across all datasets.

### Cross-Validation:
- Applied Stratified K-Fold cross-validation to ensure a balanced evaluation of model performance.

### Data Visualization: 
- Utilized bar charts, line graphs, as well as heat maps to compare the training accuracy, testing accuracy, and validation accuracy for each classifier across different data splits (20/80, 50/50, 80/20).
- Bar charts used to quickly compare how well each classifier is performing, easy to spot over/underfitting.
- Line graphs used to show how each classifier's accuracy is changing, identifies trends of how model performance is affected.
- Heat maps used to visualize the correlation between multiple variables using color intensity, summarizing complex data and highlighting anomalies 

## Technologies Used
- **Python:** The main programming language used.
- **Pandas & NumPy:** For data manipulation, encoding, and processing.
- **Scikit-learn:** For building machine learning models, encoding, cross-validation, and SMOTE.
- **Imbalanced-learn:** For addressing class imbalance using SMOTE.
- **Matplotlib & Seaborn:** For visualizing the performance of models across the datasets.
- **Jupyter Notebook:** For running and sharing code.
