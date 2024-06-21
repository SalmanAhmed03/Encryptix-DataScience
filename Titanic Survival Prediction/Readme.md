Titanic Survival Prediction

This project aims to build a machine learning model to predict the survival of passengers on the Titanic using a variety of algorithms. The dataset used includes passenger demographics, ticket information, and other relevant features.

Dataset

The dataset contains the following columns:


PassengerId: Unique ID for each passenger

Survived: Survival (0 = No, 1 = Yes)

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Name of the passenger

Sex: Gender of the passenger

Age: Age of the passenger

SibSp: Number of siblings / spouses aboard the Titanic

Parch: Number of parents / children aboard the Titanic

Ticket: Ticket number

Fare: Passenger fare

Cabin: Cabin number

Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Project Overview

The project involves the following steps:


Data Loading: Load the dataset using pandas.

Data Preprocessing: Handle missing values, encode categorical features, and select relevant features.

Data Splitting: Split the data into training and testing sets.

Feature Scaling: Standardize the feature values.

Model Training and Evaluation: Train and evaluate multiple models including Logistic Regression, Random Forest, and Gradient Boosting.

Visualization: Plot confusion matrices and ROC curves to visualize and compare model performance.

Code Explanation:

1.Data Loading and Preprocessing

2.Data Splitting and Scaling

3.Model Training and Evaluation

4.Visualization


Conclusion

This project demonstrates the process of building and evaluating machine learning models to predict Titanic survival using Logistic Regression, Random Forest, and Gradient Boosting. The models are compared using accuracy, confusion matrices, and ROC curves.
