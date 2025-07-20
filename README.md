# Breast Cancer Classification using SVM

This is a beginner-level machine learning project where I built a Support Vector Machine (SVM) classifier to predict whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset.

## Dataset
- Source: `sklearn.datasets.load_breast_cancer()`
- Features: 30 real-valued input features
- Target: `0` = malignant, `1` = benign

## ML Model
- Model used: `SVC` from scikit-learn
- Hyperparameter Tuning: `GridSearchCV` to find the best `C` and `gamma`
- Evaluation: Confusion Matrix, Classification Report, Accuracy

## Results
- Accuracy after tuning: **94%**
- Best parameters found: `C = 1`, `gamma = 0.0001`
- Confusion Matrix and classification report visualized
