
# Credit Risk Analysis Project

## Overview
This project is aimed at building a credit risk prediction model using machine learning techniques. The objective is to predict whether a person will default on their credit (target variable: `SeriousDlqin2yrs`). The dataset used for training and testing is from the **GiveMeSomeCredit** dataset.

### Key Features:
- Data preprocessing: Handling missing values, feature engineering, and feature scaling.
- Model training: Using **XGBoost** and **Random Forest** classifiers.
- Data balancing: Addressing class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique).
- Evaluation: Using **Precision-Recall Curve**, **ROC AUC**, and **Confusion Matrix** for model evaluation.

## Prerequisites

This project requires the following Python libraries:

- `pandas` - For data manipulation.
- `numpy` - For numerical operations.
- `matplotlib` - For plotting and visualizations.
- `scikit-learn` - For machine learning algorithms and metrics.
- `xgboost` - For the XGBoost model.
- `imbalanced-learn` - For SMOTE to handle class imbalance.

### Installing Dependencies

You can install all the required libraries using `pip`:

```bash
pip install xgboost imbalanced-learn scikit-learn numpy pandas matplotlib --quiet
