# Email-Spam-Detection

##  Project Overview

This project classifies emails as Spam or Ham (non-spam) using machine learning algorithms. The dataset used for this project is a publicly available spam email dataset from Kaggle. The project involves various steps, including data preprocessing, feature extraction, model training, and evaluation. The aim is to build a robust classifier that can detect spam emails efficiently.


#Objective

To build a machine learning model that can classify emails into Spam or Ham.
Handle imbalanced data using SMOTE.
Evaluate multiple machine learning models for optimal performance

#Key Features

Data Preprocessing: Cleaned the dataset, handled missing values, and removed duplicates.
Class Imbalance Handling: Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the class distribution between spam and ham emails.
Text Data Processing: Used TF-IDF (Term Frequency-Inverse Document Frequency) to vectorize text data for classification.
Machine Learning Models: Trained various models:
Logistic Regression
Naive Bayes
Random Forest
Support Vector Machine (SVM)
Model Evaluation: Evaluated the models using performance metrics such as F1-score, AUC-ROC, and Confusion Matrix.
Best Performing Model: Achieved the highest performance with Random Forest and SVM.
