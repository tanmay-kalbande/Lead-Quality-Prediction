![visitors](https://visitor-badge.laobi.icu/badge?page_id=github.com/tanmay-kalbande/Lead-Quality-Prediction&left_color=crimson&right_color=708090)
# Lead Quality Prediction

## Business Problem 

This project aims to predict the quality of sales leads as high or low potential to help prioritize sales efforts. 

## Data

The data contains information about leads like product ID, source, location, sales agent etc. The target variable is the lead status categorized as high potential or low potential.

The data has 7328 rows and 15 columns.

## Methods Used

- Exploratory Data Analysis
- Data Preprocessing
  - Handling missing values
  - Encoding categorical variables 
- Sampling using SMOTE to balance class distribution
- Modeling
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - SVM
  - Neural Network
  - Naive Bayes
  - KNN
  - XGBoost
- Hyperparameter Tuning
- Model Evaluation and Selection

## Tech Stack

- Python
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Conclusion

Several models were trained and evaluated. Random Forest performed the best with 77% accuracy and 0.77 ROC AUC. XGBoost was second best with 75% accuracy. The top models significantly improved lead prioritization compared to a basic model.

## Future Work

Some ways to improve the model:

- Try deep learning models like LSTM for sequence data
- Use larger dataset to improve performance 
- Add model explanability using SHAP values
- Deploy model to web application
