# student-dropout-MLproject-neuronetix-intern
Student Dropout Prediction
This project aims to predict student dropout rates using various machine learning algorithms. The dataset consists of features related to students' academic and personal information. The target variable indicates whether a student has dropped out, graduated, or is still enrolled.

Project Overview
Dataset
Source: Custom dataset
Features: Various academic and personal characteristics
Target: Student status (Dropout, Graduate, Enrolled)
Exploratory Data Analysis (EDA)
Distribution Analysis: Histograms for each feature to visualize data distribution.
Correlation Matrix: Heatmaps to identify relationships between features and the target variable.
Data Preprocessing
Encoding: Categorical target variable is label-encoded.
Feature Selection: Features with a correlation greater than 0.1 with the target were selected.
Handling Duplicates: Removed duplicate entries to ensure data integrity.
Scaling: Standardized features for better model performance.
Machine Learning Models
Five machine learning models were implemented to predict student dropout:

Logistic Regression
Support Vector Machine (SVM)
Random Forest Classifier
Model Performance
Accuracy: Evaluated the accuracy of each model on the test set.
Learning Curves: Plotted to visualize model performance as the training set size increases.
Results
Best Model: Logistic Regression
Accuracy: 0.75
Conclusion
This project demonstrates the ability to predict student dropout rates using various machine learning models,
with Logistic Regression achieving the highest accuracy.

Dependencies
Python
Pandas
Seaborn
Matplotlib
Scikit-learn
