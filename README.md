Breast Cancer Classification - AIML Mini Project
Project Overview
This project is a machine learning based Breast Cancer Classification System. The system predicts whether a breast tumor is Benign or Malignant using machine learning classification algorithms.

Dataset
Dataset Used: Breast Cancer Dataset

Target Column: diagnosis

Target Classes:

B = Benign
M = Malignant
The ID column was removed during preprocessing.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
Joblib
Streamlit
Machine Learning Models
The following models and techniques were applied:

SVM Manual Search
SVM GridSearchCV
SVM RandomizedSearchCV
Random Forest
AdaBoost
Gradient Boosting
XGBoost
Methodology
Dataset loading
Data preprocessing
Duplicate removal
ID column removal
Target encoding
Train-test split
Feature scaling
Manual hyperparameter search
GridSearchCV
RandomizedSearchCV
Model training
Model evaluation
Model comparison
Best model selection
Model saving
Frontend development
Model Comparison
The performance of all trained models was compared using accuracy score.

The best performing model was selected automatically based on the highest accuracy.

Saved Model Files
The following files are generated:

best_ensemble_model.pkl
scaler.pkl
columns.pkl
Frontend
A Streamlit frontend is created for making predictions using the saved best model.

How to Run
Install the required libraries:

pip install -r requirements.txt

Run the Streamlit application:

streamlit run app.py

Project Structure
Q10_Breast_Cancer_Project/

├── app.py

├── requirements.txt

├── best_ensemble_model.pkl

├── scaler.pkl

├── columns.pkl

└── README.md

Conclusion
This project demonstrates a complete machine learning pipeline for breast cancer classification, including hyperparameter tuning, ensemble learning, model comparison, best model selection, model saving, and frontend deployment.

👨‍💻 Developed By 

Sahil Karpate

Government Polytechnic Murtijapur

Computer Engineering

Session 23 AIML Assignment
