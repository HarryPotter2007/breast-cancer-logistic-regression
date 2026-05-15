Breast Cancer Classification using Logistic Regression (From Scratch)
Project Overview

This project implements a complete Logistic Regression model from scratch using only NumPy for Breast Cancer Classification.

The goal of the project is to predict whether a tumor is:

Malignant (Cancerous)
Benign (Non-Cancerous)

Unlike standard implementations using machine learning libraries, this project manually implements:

Data preprocessing
Feature normalization
Sigmoid function
Cost function
Gradient descent
Prediction pipeline
Evaluation metrics

This project helped build a strong understanding of the mathematics behind Logistic Regression and binary classification.

Dataset

Dataset used:

Breast Cancer Wisconsin Dataset

Features include:

Radius
Texture
Perimeter
Area
Smoothness
Concavity
Symmetry
Fractal Dimension

and several derived statistical measurements.

Technologies Used
Python
NumPy
Pandas
Matplotlib
Jupyter Notebook
Exploratory Data Analysis (EDA)

Performed:

Null value detection
Correlation analysis
Feature importance analysis
Scatter plot visualization

Highly correlated features included:

concave points_worst
perimeter_worst
radius_worst
Logistic Regression Implementation

The model was implemented completely from scratch.

Steps Implemented
Initialize weights and bias
Compute linear equation
Apply sigmoid activation
Compute binary cross entropy loss
Compute gradients
Update parameters using gradient descent
Repeat for multiple iterations
Mathematical Concepts Used
Sigmoid Function

σ(z) = 1 / (1 + e^(-z))

Linear Equation

z = Xw + b

Cost Function

Binary Cross Entropy Loss

Gradient Descent Update

w = w - α * dw

b = b - α * db

Model Performance
Final Results
Metric	Score
Accuracy	98.24%
Precision	96.15%
Recall	96.15%
F1 Score	96.15%

The model performed strongly on the test dataset after feature normalization.

Learning Outcomes

Through this project I learned:

How Logistic Regression works internally
Importance of feature scaling
Gradient descent optimization
Binary classification concepts
Evaluation metrics such as precision, recall, and F1-score
Real-world ML workflow fundamentals
Future Improvements

Possible future upgrades:

Deploy model using Streamlit
Add confusion matrix visualization
Compare with sklearn implementation
Add ROC-AUC analysis
Improve UI and interactivity
Repository Structure
├── data/
├── notebook.ipynb
├── main.py
├── requirements.txt
└── README.md
Author

Rushabh Borkar
