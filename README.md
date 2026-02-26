# Heart_disease_prediction

A Machine Learning web application built using Streamlit that predicts the presence of heart disease based on medical attributes. The app trains multiple classification models, compares their accuracy, and automatically selects the best-performing model for prediction.

# Features

Upload custom heart.csv dataset

Trains multiple ML classification models

Displays model accuracy comparison

Automatically selects best-performing model

Real-time heart disease prediction

Confidence level display

Interactive and clean UI using Streamlit

Technologies Used

Python

Streamlit

Pandas

NumPy

Scikit-learn

# Machine Learning Models Implemented

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Naive Bayes

Support Vector Classifier (SVC)

Gradient Boosting

# How It Works

Upload a dataset (heart.csv) containing patient medical records.

The dataset must include a 'target' column:

1 → Heart Disease Present

0 → No Heart Disease

The system:

Splits data into training and testing sets

Scales features using StandardScaler

Trains all models

Compares accuracy

The best model is selected automatically.

User can manually input patient details in the sidebar for live prediction.
