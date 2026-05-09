# machine-learning-heart-disease-analysis
Heart Disease Prediction using Machine Learning models including Logistic Regression, SVM, Random Forest, PCA, and Hyperparameter Tuning.

Project Overview

This project focuses on predicting heart disease using multiple Machine Learning classification algorithms. The dataset was preprocessed, scaled, and analyzed using various ML models including Logistic Regression, Support Vector Machine (SVM), and Random Forest Classifier.

Dimensionality reduction using Principal Component Analysis (PCA) and hyperparameter tuning using GridSearchCV were also performed to improve model performance.

**The dataset contains patient health information such as:** 

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol
Maximum Heart Rate
Exercise Angina
ST Slope
Heart Disease (Target Variable)

**Machine Learning Pipeline**
Data Loading
Data Preprocessing
One-Hot Encoding of categorical features
Outlier Removal using Z-score
Feature and Target Separation
Train-Test Split
Feature Scaling using StandardScaler
Model Training (Logistic Regression, SVM, Random Forest)
Model Evaluation using Accuracy Score
Dimensionality Reduction using PCA
Hyperparameter Tuning using GridSearchCV
Final Model Selection based on Accuracy

**Principal Component Analysis (PCA)** was applied to reduce dimensionality while preserving 95% variance.
Original Features: 15
Reduced Features: 10

**Model Accuracy**
_Logistic Regression	85.87%_ 
_SVM	86.41%_
_Random Forest	85.87%_
_Logistic Regression + PCA	83.15%_
_SVM + PCA	84.24%_
_Random Forest + PCA	87.50%_

**The best-performing model was:**
_**Random Forest + PCA
Final Accuracy: 87.5%**_
Best Hyperparameters:

{
    'max_depth': None,
    'min_samples_split': 2,
    'n_estimators': 200
}
**Technologies Used**
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Google Colab
Author

