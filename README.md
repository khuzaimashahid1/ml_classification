# Machine Learning Classification Model Evaluation
This repository contains code for evaluating various machine learning models on a dataset. The code performs data preprocessing, model training, and model evaluation using several classification algorithms. The models included in this repository are:

Nearest Neighbors
Logistic Regression
Linear SVM
RBF SVM
Decision Tree
Random Forest
Neural Net
AdaBoost
Naive Bayes

# Getting Started

## Prerequisites
Make sure you have the following libraries installed:

NumPy
Pandas
Seaborn
Matplotlib
Scikit-learn
Imbalanced-learn

## Usage
You can run the code by executing the notebook. The notebook performs the following steps:

Import the required libraries.
Load the dataset from an Excel file.
Perform data preprocessing, including scaling and encoding.
Split the dataset into training and testing sets.
Train and evaluate the models using different algorithms.
Plot the ROC curves and precision-recall curves for each model.
Perform oversampling and undersampling techniques to balance the classes.
Train and evaluate the models on the balanced dataset.
Perform hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
Train the models with the best hyperparameters.
Plot the feature importances for the best performing Random Forest model.
## Results
The code outputs the classification scores, ROC scores, classification reports, confusion matrices, ROC curves, and precision-recall curves for each model. It also plots a bar plot of the target variable and feature importances for the best performing Random Forest model.