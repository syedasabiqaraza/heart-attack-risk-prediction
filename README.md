# heart-attack-risk-prediction
Machine Learning project for predicting heart attack risk using Logistic Regression and Random Forest.


Project Overview

This project presents a machine learning-based approach to predict the risk of heart attack using patient clinical data. The goal is to assist in early detection and support preventive healthcare decision-making.

Two classification models were implemented and compared:

Logistic Regression

Random Forest Classifier

The Random Forest model achieved the best performance with approximately 87.5% accuracy.

Problem Statement

Cardiovascular diseases are one of the leading causes of death worldwide. Early identification of high-risk patients can significantly reduce mortality through timely medical intervention. This project aims to develop a predictive model that classifies patients based on their likelihood of experiencing a heart attack using supervised machine learning techniques.

Dataset Description

The dataset contains patient health records including:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol Level

Fasting Blood Sugar

Maximum Heart Rate Achieved

Exercise-Induced Angina

Other heart-related parameters

The target variable indicates whether a patient is at risk of heart attack (1) or not (0).

Methodology
1. Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Train-test split

2. Model Development

Logistic Regression (baseline model)

Random Forest Classifier (ensemble model)

3. Model Evaluation

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC Curve

Model Performance
Model	Accuracy
Logistic Regression	~85%
Random Forest	~87.5%

Random Forest outperformed Logistic Regression in overall evaluation metrics.

Feature Importance

Feature importance analysis identified key factors such as:

Age

Cholesterol

Maximum Heart Rate

Chest Pain Type

These features significantly influence heart attack risk prediction.

Risk Categorization

Predicted probabilities were categorized into:

Low Risk

Medium Risk

High Risk

This improves real-world interpretability and practical usability in healthcare settings.

Error Analysis

Special attention was given to false negatives and false positives. Minimizing false negatives is critical in healthcare applications to avoid misclassifying high-risk patients.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

How to Run the Project

Clone the repository

Install dependencies from requirements.txt

Open the notebook in Jupyter Notebook or Google Colab

Run all cells sequentially

Future Improvements

Larger and more diverse datasets

Integration of ECG time-series data

Hyperparameter tuning

Deployment as a web-based application

Author

Bibi Sabiqa Raza
Artificial Intelligence Student
Hackathon Submission Project
