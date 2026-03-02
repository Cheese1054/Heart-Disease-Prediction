# *Heart Disease Prediction Project*

## Task Objective*
* *Predict the presence of heart disease in patients using clinical data.*
* *Clean and preprocess medical datasets for machine learning readiness.*
* *Analyze health trends through Exploratory Data Analysis (EDA).*
* *Evaluate model reliability using accuracy, confusion matrices, and ROC curves.*

## Dataset Used*
* *Data Source: UCI Heart Disease Dataset (via Kaggle).*
* *Total Samples: 303 patient records.*
* *Key Features: Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), and Maximum Heart Rate (thalach).*
* *Target Variable: Binary classification (0 = No Heart Disease, 1 = Heart Disease).*

## Models Applied*
* *Algorithm: Logistic Regression (chosen for binary classification efficiency).*
* *Data Split: 80% Training set and 20% Testing set.*
* *Preprocessing: Handled missing value checks and feature scaling through the Logistic Regression solver.*

## Key Results and Findings*
* *Accuracy: The model consistently achieved an accuracy score of approximately 85% or higher.*
* *Top Predictors: Features like chest pain type, maximum heart rate, and ST depression (oldpeak) were the most significant indicators of risk.*
* *Performance: The ROC-AUC curve demonstrated high discriminative power, showing the model effectively distinguishes between healthy and at-risk patients.*
