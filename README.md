# Lead Quality Prediction Project

## Business Problem

This project aims to identify high potential leads for a company to improve sales effectiveness. Predicting lead quality helps prioritize sales efforts.

## Data Overview

The dataset contains 7328 rows and 15 columns capturing information about leads like product, source, location etc. Target is lead status as high/low potential. 

## Project Goal

Build a classification model to predict if a lead is high or low quality. Compare performance of different ML algorithms.

## Methods Used

- Exploratory Data Analysis 
- Data Preprocessing (encoding, handling null values)
- Balancing classes using SMOTE sampling
- Modeling with Logistic Regression, SVM, Random Forest, XGBoost etc
- Hyperparameter Tuning to optimize models
- Evaluate models on accuracy, AUC ROC, F1 score

## Key Results

- Random Forest performs best with 77% accuracy and 0.77 F1 score
- XGBoost comes second with 75% accuracy
- Significant lift over a baseline model

## Conclusion

Random Forest works well for lead quality prediction. This project provides a template for using ML to improve sales conversions.

## Future Work

- Try neural network models like LSTM 
- Add model explanations using SHAP values
- Deploy model to web application
