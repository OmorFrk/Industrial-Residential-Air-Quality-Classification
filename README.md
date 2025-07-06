# Industrial-Residential-Air-Quality-Classification
This project aims to classify cities as Industrial or Residential based on their air quality data.

# Overview
Dataset Source: Kaggle (Air Quality Dataset).
The dataset contains various air pollutant levels including:
CO, NO₂, SO₂, O₃, PM2.5, PM10, and more.
Objective:
Predict whether a city belongs to an Industrial or Residential area based on air quality parameters.

# Key Highlights
Feature Engineering: Extracted useful time-based features such as: Hour, Day of Week, Month from the Date column.
Preprocessing: Dropped 'City' column to prevent overfitting (as it directly correlates with 'Type').
Applied feature scaling and label encoding for effective model performance.
Multiple classification algorithms were implemented and compared:
Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Kernel SVM, Naive Bayes, Decision Tree, Random Forest

# Accuracy Scores:
| Algorithm                    | Accuracy (%) |
| ---------------------------- | ------------ |
| Logistic Regression          | 97.396       |
| K-Nearest Neighbors (KNN)    | 98.497       |
| Support Vector Machine (SVM) | 97.548       |
| Kernel SVM                   | 98.846       |
| Naive Bayes                  | 92.349       |
| Decision Tree                | 99.020       |
| **Random Forest (Best)**     | **99.324**   |

# Conclusion
Among all models, Random Forest Classification achieved the highest accuracy of 99.324%, highlighting its effectiveness in this classification task.
The project demonstrates how air quality metrics can be effectively used to distinguish between industrial and residential zones.

# Project Goals Achieved:
Successful feature engineering and preprocessing.
Implementation and comparison of multiple classification algorithms.
Identified key features contributing to classification (notably SO₂).
Avoided overfitting by removing location-specific identifiers.

#  Future Improvements:
Hyperparameter tuning for further optimization.
Testing with more diverse datasets from other regions.
Model explainability (SHAP, LIME) for deeper insights.

# 📂 Repository Contains:
Jupyter Notebook with complete code and analysis.
Preprocessing pipeline.
Model training & evaluation results.
