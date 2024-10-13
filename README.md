# diabetes_prediction
# Diabetes Prediction Project

## Overview

This project aims to predict whether a person is diabetic or not based on various medical measurements. The model uses machine learning techniques to analyze input data such as glucose levels, blood pressure, insulin levels, and other medical features, and predicts the likelihood of diabetes.

The project leverages Python and popular machine learning libraries like Scikit-learn for data processing, model training, and evaluation.

## Dataset

The dataset contains medical details of patients, including the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function that scores likelihood of diabetes based on family history
- **Age**: Age in years

The target variable is:
- **Outcome**: 1 if the person is diabetic, 0 if the person is not diabetic

## Requirements

To run this project, the following Python packages are required:

- `numpy`
- `pandas`
- `scikit-learn`
- `joblib`
- `matplotlib` (optional, for visualizations)

You can install these packages using pip:

```bash
pip install -r requirements.txt
