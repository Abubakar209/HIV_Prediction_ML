# HIV Infection Prediction using Machine Learning

This project applies multiple machine learning models to predict HIV infection using clinical and demographic data. It compares Logistic Regression, Decision Trees, Random Forest, and CatBoost.

## Key Features
- Data preprocessing: normalization, SMOTE for class imbalance
- Model comparison using accuracy, precision, recall, and F1-score
- Hyperparameter tuning with Optuna
- Feature importance analysis

## Results
CatBoost achieved the best results:
- Accuracy: 90%
- Precision: 88%
- Recall: 87%
- F1-Score: 82%

## Dataset
Sourced from the AIDS Clinical Trials Group Study 175.

## Requirements
```bash
pip install -r requirements.txt
