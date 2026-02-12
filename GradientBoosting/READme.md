# Gradient Boosting Notebooks (Classification + Regression)

This repository contains two Jupyter notebooks that demonstrate **Gradient Boosting** on two classic tabular datasets:
- **Heart Disease** (binary classification)
- **Concrete Compressive Strength** (regression)

The focus is on a clean, end-to-end workflow: **load data → quick EDA → train/test split → model training → evaluation → hyperparameter search**.

---

## Notebooks

### 1) Heart Disease — Gradient Boosting Classification
**File:** `HearthDiseaseGBClassification (1).ipynb`

**Objective:** Predict the binary `target` label using clinical features (e.g., age, chest pain type, resting blood pressure, cholesterol, etc.).

**What it includes:**
- Data loading (CSV)
- Basic EDA (distribution and relationship plots)
- `train_test_split`
- `GradientBoostingClassifier`
- Model evaluation with `classification_report` and `confusion_matrix`
- Hyperparameter tuning with `GridSearchCV`

---

### 2) Concrete — Gradient Boosting Regression
**File:** `ConcreteGBRegressor.ipynb`

**Objective:** Predict concrete **compressive strength** (`Strength`) from mix design features (cement, water, aggregates, age, and optional additives).

**What it includes:**
- Data loading (CSV)
- Basic EDA
- `train_test_split`
- Gradient boosting concept demo via residual learning (weak learners)
- `GradientBoostingRegressor`
- Evaluation with `r2_score`
- Hyperparameter tuning with `RandomizedSearchCV`

---
