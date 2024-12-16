# Air-quality-model
Air Quality Prediction Model
This repository contains a machine learning project aimed at predicting air quality categories based on pollution metrics. Using a supervised learning approach, the model classifies air quality into predefined categories based on environmental data.

Features of the Project
Dataset: The model is trained on a dataset containing various pollution metrics such as PM2.5, PM10, NO2, etc., with a total of 5,000 entries and 10 columns.
Preprocessing:
Encoded categorical labels for the target variable (Air Quality).
Normalized feature values using StandardScaler.
Split the data into 80% training and 20% testing sets.
Model: A DecisionTreeClassifier was used to classify air quality into categories.
Performance
Accuracy: The model achieved an accuracy of 90.47% on the test set.
Future steps include improving the evaluation with metrics like precision, recall, and F1-score, as well as experimenting with alternative models.
