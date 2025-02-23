# Heart-Disease-Predictor

This project aims to predict the likelihood of heart disease based on various clinical features using a logistic regression model. The model achieves 85% accuracy and incorporates several techniques to enhance performance and prevent overfitting.

# Project Overview

#Model: 
Logistic Regression with gradient descent and L1/L2 regularization to improve generalization and prevent overfitting.

# Accuracy: 
Achieved 85% accuracy on the test dataset.

# Key Features
# 1. Data Preprocessing:
Utilized StandardScaler for feature normalization to scale numerical features.
Applied OneHotEncoder to transform categorical variables into binary features.
Engineered polynomial features using PolynomialFeatures to capture non-linear relationships and improve model performance.

# 2. Model Optimization:
Experimented with different solvers for logistic regression, including SAGA and LBFGS, to fine-tune convergence and performance.
Implemented L1/L2 regularization (Lasso/Ridge) to prevent overfitting and enhance model stability.

# 3. Hyperparameter Tuning:
Performed hyperparameter tuning to identify the optimal settings for the model, improving its ability to generalize on unseen data.
