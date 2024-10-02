# Machine-learning-From-Disaster-Titanic-Survival-Problem
This project is a solution for the Titanic: Machine Learning from Disaster competition on Kaggle. The goal is to predict whether a passenger survived or not based on various features like age, sex, fare, and family relationships.

Project Overview
The project involves the following steps:

Data Preprocessing

Handle missing values for key features like Age, Embarked, and Fare.
Create new features such as FamilySize (based on the number of siblings, spouses, and parents aboard).
Convert categorical features (e.g., Sex and Embarked) into numerical values using one-hot encoding.
Drop irrelevant columns like Cabin, Name, and Ticket.
Model Building

A Random Forest Classifier is used to predict passenger survival.
The model is trained on the preprocessed dataset and evaluated on a validation set using metrics like accuracy, confusion matrix, and classification report.
Prediction and Submission

The trained model is applied to the test dataset after similar preprocessing.
Predictions are made for the test set and a submission file is generated in the required format for Kaggle.

The competetion and data can be found here : https://www.kaggle.com/competitions/titanic

Will Cukierski. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic
