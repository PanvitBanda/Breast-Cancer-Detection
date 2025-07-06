Breast Cancer Detection – ML

This project aims to build a binary classification model that predicts whether a tumor is **malignant** or **benign** using the Breast Cancer Wisconsin dataset.

Objectives
- Load and explore clinical data from scikit-learn
- Train a machine learning model (Random Forest)
- Evaluate accuracy, precision, recall, and F1-score
- Plot ROC curve and calculate AUC
- Perform real-time predictions on new input

Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib

Models & Metrics
- RandomForestClassifier  
- Confusion Matrix  
- Classification Report  
- ROC Curve (AUC score)

Dataset
Built-in breast cancer dataset from `sklearn.datasets.load_breast_cancer`.  
It contains 569 samples with 30 numeric features each.

Evaluation
The model shows strong classification performance.  
ROC curve is used to visualize true vs false positive rates.
