# Loan-Eligibility-Prediction
Project for Machine Learning
This project aims to develop and evaluate machine learning models to predict loan approval statuses using a dataset from "train.csv". The data preparation process involves dropping irrelevant columns, such as "Loan_ID" and "Married", and handling missing values by removing incomplete records. Categorical variables, including "Gender", "Education", "Self_Employed", and "Property_Area", are encoded using LabelEncoder. The cleaned dataset is divided into features (x) and labels (y), with "Loan_Status" as the target variable.

The dataset is split into training and testing sets using train_test_split. Multiple machine learning models are trained and evaluated, including Support Vector Machine (SVC), Gaussian Naive Bayes, Multinomial Naive Bayes, Random Forest, and Logistic Regression. Hyperparameter tuning is performed using GridSearchCV to identify the best parameters and highest accuracy for each model.

Logistic Regression emerged as the most effective model. It was first trained on the training set and evaluated on the test set, yielding an accuracy score of 81.3%. Subsequently, the model was retrained on the entire dataset and evaluated on a new test dataset prepared similarly to the initial training dataset, achieving an accuracy of 81.9%.

This project demonstrates the end-to-end process of data preparation, model selection, hyperparameter tuning, and evaluation. By showcasing practical steps for predictive modeling in a real-world context, it provides a comprehensive approach to ensure robust model performance evaluation. The project highlights the importance of thorough data preprocessing and the effectiveness of Logistic Regression in predicting loan approval statuses.
