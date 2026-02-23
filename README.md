# Diabetes-Prediction-Model
This project builds a machine learning model to predict whether a patient has diabetes based on medical attributes such as glucose level, BMI, insulin, and blood pressure.

**Problem Statement**

Early detection of diabetes can help reduce health risks. This project aims to classify patients as diabetic or non-diabetic using historical medical data.

**Dataset**

Pima Indians Diabetes Dataset

768 records

8 medical features

Target variable: Outcome (0 = Non-diabetic, 1 = Diabetic)

**Steps Performed**

Data cleaning and handling missing values

Exploratory Data Analysis (EDA)

Feature scaling using StandardScaler

Model training using K-Nearest Neighbors (KNN)

Hyperparameter tuning using GridSearchCV

Model evaluation using Accuracy, Precision, Recall, and F1-score

**Feature Importance Analysis**

To make the model more interpretable, a Random Forest classifier was implemented to identify which features contribute most to diabetes prediction.

The analysis showed that features such as Glucose level and BMI have the highest impact on prediction, making them key indicators of diabetic risk.

This step improves the explainability of the model and makes it more meaningful for real-world healthcare applications.

**Technologies Used**

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

**Results**

Test Accuracy: 77%

Evaluated using confusion matrix and classification metrics
