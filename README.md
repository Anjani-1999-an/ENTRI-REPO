# DigitalExposome Classification Project

## Project Description

This machine learning project focuses on classifying individuals based on the DigitalExposome dataset, which captures behavioral and environmental digital exposure factors. The goal is to predict the target class using various classification algorithms and evaluate their performance to identify the best-performing model.

- **Objective**: Predict the target class based on digital exposure features.
- **Approach**: Trained and evaluated multiple ML models with hyperparameter tuning and model comparison.

## Dataset

- **Dataset Source**: *Mendeley Data  *
- **Description**:
  - The dataset includes features such as digital behavior, environmental exposure, and lifestyle metrics.
  - The target variable is a categorical label indicating a specific class relevant to digital exposure classification.

## ML Models Used

- **Algorithms**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - AdaBoost Classifier
  - Support Vector Classifier (SVC)
- **Techniques**:
  - Standardization and train-test split
  - Hyperparameter tuning using `GridSearchCV`
  - Model evaluation using various metrics
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` for modeling and evaluation

## Evaluation Metrics

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

## Results

- Hyperparameter tuning significantly improved model performance.
- Random Forest and Gradient Boosting classifiers showed the best balance across all metrics.
- Visualizations include heatmaps of confusion matrices and ROC curves for comparison.

## Conclusion

This project demonstrates a comparative analysis of multiple classification algorithms on the DigitalExposome dataset. Future improvements may include:
- Incorporating feature selection and dimensionality reduction techniques.
- Using ensemble stacking or deep learning methods.
- Deploying the best model using a web framework like Flask or FastAPI.