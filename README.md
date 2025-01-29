# Early Diabetes Detection: An Advanced Machine Learning Project

This project focuses on the early prediction of diabetes using advanced machine learning techniques. It combines several machine learning models, such as Decision Trees, Random Forests, Gradient Boosting, AdaBoost, and Neural Networks, to analyze health-related data and improve the accuracy of predictions.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)

## Introduction
Diabetes is a chronic condition with severe health consequences if not diagnosed early. This project explores machine learning models to predict diabetes based on features such as age, gender, BMI, blood glucose levels, and more.

The AdaBoost model achieved the best results with an accuracy of 97% and an AUC of 0.98.

## Dataset
The dataset contains key demographic and medical information, including:
- Age
- Gender
- BMI
- HbA1c Levels
- Blood Glucose Levels
- History of Smoking, Hypertension, and Heart Disease

## Methodology
The project involved the following steps:
1. **Data Preprocessing:** Removing null values, reclassifying smoking history, and data visualization.
2. **Model Selection:** Training and validating models using cross-validation.
3. **Model Comparison:** Evaluating models based on accuracy, AUC, and runtime.

## Results
| Model             | Accuracy | AUC | CV Runtime (seconds) |
|-------------------|----------|-----|----------------------|
| AdaBoost          | 0.97     | 0.98| 22.11                |
| Gradient Boosting | 0.97     | 0.94| 14.29                |
| Neural Network    | 0.96     | 0.96| 37.42                |
| Random Forest     | 0.97     | 0.96| 34.48                |
| Decision Tree     | 0.96     | 0.86| 0.61                 |

## Technologies Used
- **Programming Language:** Python
- **Libraries:** scikit-learn, Matplotlib, NumPy, Pandas
- **Visualization:** Heatmaps and bar charts
- **Machine Learning Models:** Decision Trees, Random Forest, AdaBoost, Neural Networks
