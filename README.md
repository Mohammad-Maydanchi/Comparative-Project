# Heart Disease Prediction: Comparative Study of ML Models
This repository contains the code, dataset processing, and evaluation results from our research paper:

Comparative Study of Decision Tree, AdaBoost, Random Forest, Naïve Bayes, KNN, and Perceptron for Heart Disease Prediction
Published at IEEE 

# Project Overview
Heart disease remains the leading cause of death worldwide. Early prediction of cardiovascular conditions can dramatically improve patient outcomes. In this project, we compare six machine learning classification models for predicting heart disease using real-world health survey data.

Models Evaluated
AdaBoost

Random Forest

Decision Tree

Naïve Bayes

K-Nearest Neighbors (KNN)

Perceptron

# Objective
Evaluate and compare classification models based on their ability to predict the minority class (patients with heart disease) using:

F1-score (Class 1)

AUC (Area Under the ROC Curve)

Due to the dataset imbalance (only 8.5% positive cases), we focus on metrics that reflect true performance on the critical minority class.

# Dataset
Source: CDC's Behavioral Risk Factor Surveillance System (via Kaggle)

Size: ~320,000 records

Target Variable: HeartDisease (Yes/No)

The dataset includes 18 features, such as:

Age category

BMI

Smoking, Alcohol use

Sleep time, Mental & Physical health days

Diabetes, Stroke history

Gender, Race, and more

Note: SMOTE was applied to handle class imbalance during training.

#  Methods
Preprocessing:

Categorical encoding

Feature scaling

SMOTE for minority oversampling

# Evaluation:

K-Fold Cross-Validation

Class-wise Precision, Recall, F1-score

ROC & AUC analysis
