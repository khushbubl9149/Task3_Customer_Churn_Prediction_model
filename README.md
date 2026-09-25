# Task3_Customer_Churn_Prediction_model

# Customer Churn Prediction

## About the Project

This project is part of my machine learning internship work. The goal is to predict whether a customer is likely to leave a company using historical customer data.

I used customer information such as age, geography, credit score, account balance, and active membership status to train machine learning models.

## Dataset

The dataset contains customer details and a target column called `Exited`.

- `0` – Customer stayed
- `1` – Customer exited

Before training the models, I removed unnecessary columns and prepared the numerical and categorical features.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Joblib

## Machine Learning Models

I trained and compared three classification models:

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

## Project Workflow

1. Loaded and explored the dataset.
2. Performed exploratory data analysis.
3. Removed unnecessary columns.
4. Separated the features and target variable.
5. Encoded categorical features.
6. Scaled numerical features.
7. Split the data into training and testing sets.
8. Trained three machine learning models.
9. Compared the models using evaluation metrics.
10. Saved the selected model using Joblib.

## Evaluation Metrics

I used the following metrics to evaluate the models:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

The model comparison results are saved in:

`churn_model_comparison.csv`

## Saved Model

The selected model was saved as:

`customer_churn_prediction_model.pkl`

The model was selected based on the F1 Score from the comparison results.

## What I Learned

Through this project, I practiced data preprocessing, exploratory data analysis, machine learning classification, model evaluation, and saving trained models for future use.

## Author

Khushabu Bansal
