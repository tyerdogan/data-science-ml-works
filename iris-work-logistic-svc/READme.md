# Iris Flower Assignment

## Overview
This project builds a Machine Learning model to predict the species of Iris flowers using the classic **Iris Dataset**.  
The main goal is to train and compare two baseline classifiers and evaluate their performance.

## Dataset
The dataset contains measurements for three Iris species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

**Features**
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Project Workflow

### 1) Exploratory Data Analysis (EDA)
- Visualized feature distributions using **box plots**
- Analyzed feature relationships using a **correlation heatmap**

**Observation:** *Petal Length* and *Petal Width* provide the clearest separation between species and appear to be the most informative features.

### 2) Data Preparation
- Checked for missing values (dataset is clean)
- Converted species labels into numeric values (**Label Encoding**)
- Split the data into **training** and **test** sets
- Scaled the features to support better model performance

### 3) Modeling
Trained two classic classifiers:
- **Logistic Regression**
- **Support Vector Machine (SVM)**

## Results & Notes
- The Iris dataset is **small and very clean**, so both models achieved **the same performance**.
- Baseline models reached **1.0 test accuracy**, so there was **limited room for improvement** with further tuning.
- I also included **GridSearchCV as an optional step** to demonstrate hyperparameter tuning, but it did not meaningfully improve results due to the already perfect baseline performance.
