# Heart-Disease-Prediction
# Overview
This repository contains a machine learning model to predict the likelihood of heart disease in patients. The model is trained on the well-known Heart Disease dataset and utilizes various machine learning algorithms to provide accurate predictions.

# Dataset
The dataset used in this project is the Cleveland Heart Disease dataset from the UCI Machine Learning Repository. It contains 14 features related to heart health, such as age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting ECG results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, and thalassemia.

# Features
* Age
* Sex
* Chest Pain Type (4 values)
* Resting Blood Pressure
* Serum Cholesterol in mg/dl
* Fasting Blood Sugar > 120 mg/dl
* Resting ECG Results (0, 1, 2)
* Max Heart Rate Achieved
* Exercise-Induced Angina
* ST Depression Induced by Exercise Relative to Rest
* The Slope of the Peak Exercise ST Segment
* Number of Major Vessels (0-3) Colored by Fluoroscopy
* Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)

# Requirements
* Python 3.x
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

# Usage
* Data Preprocessing: The data is cleaned and preprocessed to handle missing values, categorical encoding, and normalization.
* Model Training: Different machine learning models (Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, etc.) are trained and evaluated.
* Prediction: The best performing model is used to make predictions on new data.

# Results
The model's performance is evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC. The results are visualized using confusion matrix, ROC curves, and feature importance plots.
