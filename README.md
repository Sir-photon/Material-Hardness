PROJECT TITLE: 
Material Hardness Prediction Model

DESCRIPTION: 	
This document provides an in-depth analysis of three different algorithms for predicting material hardness. The dataset contains 10,407 rows and 13 columns.

PROGRAM: 
The solution began with simple code to view dataset information and description. Then, noise in the dataset was checked, followed by visualization with a brief exploratory data analysis (EDA) of the dataset. Subsequently, modeling commenced by setting up the dataset into features and target. Three different algorithms (XGBoost, RandomForest, and Linear Regression) were employed along with k-fold cross-validation.

After finalizing the best algorithm using cross_val_score evaluation, the `feature_importances_` method was utilized to visualize the contributions of each feature in the model.
