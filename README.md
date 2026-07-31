# Breast Cancer Classification - AIML Mini Project

## Project Overview

This project is a machine learning based Breast Cancer Classification System. The system predicts whether a breast tumor is Benign or Malignant using machine learning classification algorithms.

## Dataset

Dataset Used: Breast Cancer Dataset

Target Column: diagnosis

Target Classes:
- B = Benign
- M = Malignant

The ID column was removed during preprocessing.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib
- Streamlit

## Machine Learning Models

The following models and techniques were applied:

1. SVM Manual Search
2. SVM GridSearchCV
3. SVM RandomizedSearchCV
4. Random Forest
5. AdaBoost
6. Gradient Boosting
7. XGBoost

## Methodology

1. Dataset loading
2. Data preprocessing
3. Duplicate removal
4. ID column removal
5. Target encoding
6. Train-test split
7. Feature scaling
8. Manual hyperparameter search
9. GridSearchCV
10. RandomizedSearchCV
11. Model training
12. Model evaluation
13. Model comparison
14. Best model selection
15. Model saving
16. Frontend development

## Model Comparison

The performance of all trained models was compared using accuracy score.

The best performing model was selected automatically based on the highest accuracy.

## Saved Model Files

The following files are generated:

- best_ensemble_model.pkl
- scaler.pkl
- columns.pkl

## Frontend

A Streamlit frontend is created for making predictions using the saved best model.

## How to Run

Install the required libraries:

pip install -r requirements.txt

Run the Streamlit application:

streamlit run app.py

## Project Structure

Q10_Breast_Cancer_Project/

├── app.py

├── requirements.txt

├── best_ensemble_model.pkl

├── scaler.pkl

├── columns.pkl

└── README.md

## Conclusion

This project demonstrates a complete machine learning pipeline for breast cancer classification, including hyperparameter tuning, ensemble learning, model comparison, best model selection, model saving, and frontend deployment.
