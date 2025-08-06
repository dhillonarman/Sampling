# Model-Performance-with-Data-Sampling-

Introduction 
This project evaluates the impact of various sampling techniques on the performance of machine learning models. The goal is to demonstrate how different data sampling methods affect classification accuracy using multiple models.

Key Features
Handling Class Imbalance: SMOTE (Synthetic Minority Oversampling Technique) is used to balance the class distribution.

Five Sampling Techniques:
Simple Random Sampling: Randomly selects a subset of the data.
Stratified Sampling: Ensures the proportion of each class in the sample matches the original dataset.
Systematic Sampling: Selects data points at regular intervals.
Cluster Sampling: Divides data into clusters and selects samples from one or more clusters.
Bootstrap Sampling: Samples data with replacement to create a new dataset.

Sample Sizes
Different sampling techniques use different formulas to determine sample size, as discussed in the discussion.

Machine Learning Models
The project evaluates the following classifiers on the balanced dataset created by different sampling techniques:
Logistic Regression
Decision Tree
Random Forest
XGBoost
Gradient Boosting
Each model is trained and tested on datasets created using the above sampling techniques, and their classification accuracy is compared.

Dataset
The dataset used is a credit card dataset, containing:

Input Features: Independent variables representing various features of the dataset.
Target Variable: A column named Class, which is imbalanced.

Sampling Techniques
The following sampling techniques are implemented to create samples of balanced datasets:

Simple Random Sampling: Randomly selects a subset of the data.
Stratified Sampling: Ensures the proportion of each class in the sample matches the original dataset.
Systematic Sampling: Selects every k-th data point from the dataset.
Cluster Sampling: Divides the data into clusters based on the Time column, and samples from one or more clusters.
Bootstrap Sampling: Samples data with replacement to create a new dataset.

Result
The project evaluates the performance of each machine learning model using the five sampling techniques, and prints the accuracy for each combination. At the end, the best-performing sampling technique and model are displayed.

