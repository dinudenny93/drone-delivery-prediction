# Predictive Analytics for Drone Delivery

## Battery Consumption Prediction and Flight Feasibility Assessment Using Machine Learning

### 1. Project Overview

This project focuses on predicting drone battery energy consumption using machine learning techniques. It also explores how predicted energy consumption can be used to assess preliminary flight feasibility.

### 2. Project Objectives

- Analyse drone flight data.
- Calculate battery energy consumption.
- Investigate the relationship between flight parameters and energy consumption.
- Develop Linear Regression and Random Forest models.
- Compare model performance.
- Estimate remaining battery energy for a planned flight.

### 3. Dataset

The original dataset contained 209 flight records. After data cleaning and preprocessing, 196 records were selected for machine learning.

The dataset includes:
- Flight speed
- Payload weight
- Maximum altitude
- Flight route
- Battery energy consumption

### 4. Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

### 5. Machine Learning Models

Two regression algorithms were developed:

1. Linear Regression
2. Random Forest Regression

### 6. Model Performance

| Evaluation Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 1.425 Wh | 0.689 Wh |
| RMSE | 1.698 Wh | 0.870 Wh |
| R² | 0.848 | 0.960 |

Random Forest achieved better predictive performance on the test dataset.

### 7. Key Findings

- Random Forest achieved an R² score of 0.960.
- Speed was the most influential model feature.
- Maximum altitude was the second most influential feature.
- The model was used for a preliminary battery feasibility assessment.

### 8. Project Files

This repository contains the Jupyter Notebook, processed dataset, prediction results, feature importance results and data visualisations.

### 9. Team Members

- Dinu Denny
- Mohan

### 10. Project Limitations

The study uses a relatively small dataset. Weather conditions, wind speed, battery ageing and return-flight energy requirements were not included in the predictive model. Therefore, the feasibility assessment is preliminary and is not a real-world flight safety certification.
