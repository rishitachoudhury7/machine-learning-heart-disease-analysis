# machine-learning-heart-disease-analysis
Heart Disease Prediction using Machine Learning models including Logistic Regression, SVM, Random Forest, PCA, and Hyperparameter Tuning.

Project Overview

This project focuses on predicting heart disease using multiple Machine Learning classification algorithms. The dataset was preprocessed, scaled, and analyzed using various ML models including Logistic Regression, Support Vector Machine (SVM), and Random Forest Classifier.

Dimensionality reduction using Principal Component Analysis (PCA) and hyperparameter tuning using GridSearchCV were also performed to improve model performance.

Dataset
The dataset contains patient health information such as:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Maximum Heart Rate
Exercise Angina
ST Slope
Heart Disease (Target Variable)
Machine Learning Pipeline
Data Loading
Data Preprocessing
One-Hot Encoding of categorical variables
Outlier Removal using Z-score
Train-Test Split
Feature Scaling using StandardScaler
Model Training
PCA for Dimensionality Reduction
Hyperparameter Tuning
Model Evaluation
Models Used
Logistic Regression
Support Vector Machine (SVM)
Random Forest Classifier
PCA

Principal Component Analysis (PCA) was applied to reduce dimensionality while preserving 95% variance.

Original Features: 15
Reduced Features: 10
Model Accuracy
Model	Accuracy
Logistic Regression	85.87%
SVM	86.41%
Random Forest	85.87%
Logistic Regression + PCA	83.15%
SVM + PCA	84.24%
Random Forest + PCA	87.50%
Best Model

The best-performing model was:

Random Forest + PCA

Final Accuracy:

87.5%

Best Hyperparameters:

{
    'max_depth': None,
    'min_samples_split': 2,
    'n_estimators': 200
}
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Google Colab
Author

Your Name Here
