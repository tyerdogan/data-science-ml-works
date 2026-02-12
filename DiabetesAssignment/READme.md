# Diabetes Classification – Missing Data Strategy Comparison

This notebook compares preprocessing strategies and classifiers on the Pima Indians Diabetes dataset.

## Goal
Evaluate how handling missing values in **Insulin** and **SkinThickness** affects model performance:
- **Scenario A:** Replace invalid zeros with NaN, then fill missing Insulin & SkinThickness with **median**
- **Scenario B:** Remove Insulin & SkinThickness features and train models on the remaining features

## Preprocessing
- Convert physiologically invalid zeros to `NaN` for clinical variables (e.g., Glucose, BloodPressure, BMI, etc.)
- Handle missing values using median (train-derived medians for stability)
- Apply `StandardScaler` for scale-sensitive models (e.g., Logistic Regression, SVM)

## Models
- Logistic Regression
- AdaBoost
- SVM (RBF)
- Gaussian Naive Bayes

