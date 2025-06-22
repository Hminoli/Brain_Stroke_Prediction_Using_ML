# Early Detection of Brain Stroke Using Machine Learning

## Overview

This project aims to predict the risk of brain stroke using machine learning techniques. Stroke is a serious medical condition that can lead to permanent disability or death. Early prediction can help in taking preventive measures and reducing risk. This project applies supervised learning models to clinical and lifestyle data to identify individuals who are more likely to suffer a stroke.

## Dataset

The dataset used in this project was obtained from Kaggle and contains clinical and demographic information of 4981 individuals. The dataset includes:

- Age
- Gender
- Hypertension
- Heart disease
- Marital status
- Work type
- Residence type
- Average glucose level
- BMI
- Smoking status
- Stroke (target variable)

## Problem Statement

The goal is to build machine learning models that can accurately classify whether a person is likely to experience a stroke based on their health and lifestyle features. The dataset is imbalanced, as only about 5% of individuals have had a stroke.

## Methods Used

- **Data Preprocessing**: Handled missing values, encoded categorical variables, and applied feature scaling.
- **SMOTE**: Used to balance the dataset by oversampling the minority class (stroke cases).
- **Machine Learning Models**:
  - Logistic Regression
  - Naïve Bayes
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest
  - XGBoost

## Evaluation Metrics

Models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

## Key Findings

- **XGBoost** achieved the best performance with an accuracy of 91.6% and an AUC of 0.94.
- Important predictors of stroke included:
  - Work type
  - Age
  - Smoking status
- SMOTE was effective in improving model performance on the imbalanced dataset.

## Conclusion

This project shows the potential of using machine learning to support early detection of stroke. By identifying high-risk individuals based on clinical and lifestyle data, the models can be integrated into decision-support tools for healthcare professionals.

## Tools and Technologies

- Python
- Scikit-learn
- XGBoost
- Logistic Regression
- Naïve Bayes
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Pandas, NumPy, Matplotlib, Seaborn

## Author

W. A. D. Himansa Minoli  
University of Colombo  
BSc Honours in Applied Statistics

