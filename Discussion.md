Introduction
This project evaluates different sampling techniques on machine learning model performance.

Different formulas for sample sizes considered are:
 n = (Z^2 * p * (1-p)) / E^2
 n = (Z^2 * p * (1-p)) / (E/S)^2
 n = (Z^2 * p * (1-p)) / (E/C)^2
 
The following sampling methods are included:
Simple Random Sampling
Stratified Sampling
Systematic Sampling
Cluster Sampling
Bootstrap Sampling Methods

The following machine learning models are used in the evaluation:
Logistic Regression
Decision Tree
Random Forest
XGBoost
Gradient Boosting

Results
The best sampling technique for each model based on accuracy is:
Logistic Regression performs best with Bootstrap Sampling.
Decision Tree performs best with Random Sampling.
Random Forest, XGBoost, and Gradient Boosting all perform best with Cluster Sampling.
