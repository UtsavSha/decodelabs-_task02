# Fraud Detection Pipeline Using Machine Learning

## Project Overview

This project aims to detect fraudulent credit card transactions using supervised machine learning techniques. Since fraud datasets are highly imbalanced, SMOTE (Synthetic Minority Oversampling Technique) was used to balance the classes before model training.

## Dataset

Credit Card Fraud Detection Dataset (creditcard.csv)

## Objectives

* Handle class imbalance using SMOTE
* Train Logistic Regression and Random Forest models
* Evaluate models using Precision, Recall, F1-Score, and ROC-AUC
* Compare model performance
* Perform hyperparameter tuning

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Matplotlib
* Seaborn

## Machine Learning Workflow

### Data Preprocessing

* Missing value handling
* Feature scaling using StandardScaler
* Train-Test Split

### Class Imbalance Handling

* SMOTE (Synthetic Minority Oversampling Technique)

### Models Implemented

1. Logistic Regression
2. Random Forest Classifier

### Hyperparameter Tuning

* GridSearchCV
* Cross Validation

## Evaluation Metrics

* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

## Visualizations

* Class Distribution
* Confusion Matrix
* ROC Curve
* Feature Importance Plot

## Results

Random Forest generally achieved better performance than Logistic Regression in detecting fraudulent transactions due to its ability to capture complex patterns in the data.

## Project Structure

├── creditcard.csv
├── fraud_prediction_results.csv
├── Fraud_Detection_Pipeline.ipynb
├── README.md

## How to Run

1. Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

2. Run the notebook or script

python fraud_detection.py

## Future Improvements

* XGBoost Implementation
* LightGBM Model
* Real-Time Fraud Detection System
* Model Deployment using Streamlit

## Outcome

A robust fraud detection pipeline capable of identifying fraudulent transactions with high recall and ROC-AUC performance.
