DigitalExposome Mental Health Classifier

Project Description

This project is an interactive web application that uses the DigitalExposome dataset to train, compare, and visualize multiple machine learning models for mental health state classification. It enables users to upload their own data, automatically preprocess it, and identify the best-performing model for predicting mental health categories based on physiological and environmental sensor features.

- Dataset
Dataset Source: DigitalExposome-Dataset.csv

Description:
The dataset contains physiological and environmental sensor measurements, including:

Features: IBI, HR, NO2, Noise, NH3, PM10, CO, PM25, PM1, EDA, BVP

Target Variable: Label (integer values 1–5, representing mental health state categories)

- ML Model
Algorithms Used:

Logistic Regression

K-Nearest Neighbors

Decision Tree

Random Forest

Gradient Boosting

Support Vector Machine (SVM, RBF Kernel)

Libraries:

scikit-learn

pandas

numpy

matplotlib

seaborn

streamlit

- Evaluation Metrics
Accuracy

Confusion Matrix

(Optionally, you can extend to Precision, Recall, F1 Score, ROC-AUC for multi-class)

- Results
The app displays accuracy for each model and confusion matrices for model predictions.

Users can interactively compare models and visualize their performance.

(Add screenshots of the model comparison chart and confusion matrix here if available.)

- Conclusion
This project demonstrates a practical approach to mental health state classification using sensor data and machine learning. The interactive app allows rapid benchmarking of different models, and can be extended with additional metrics, feature importance analysis, or support for new data sources in the future.
