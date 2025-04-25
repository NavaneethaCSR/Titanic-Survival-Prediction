# Titanic-Survival-Prediction

1. The dataset is loaded directly from a public Google Sheets CSV link and selected relevant feature  and target variable about Titanic passengers such as:

Pclass

Sex

Age

SibSp

Parch

Fare

Embarked

Survived (target)


2. Features
Data Cleaning: Handles missing values in Age and Fare.
Encoding: Converts categorical variables like Sex and Embarked into a numerical format.
Feature Scaling: Normalizes the data using StandardScaler.
Model: Uses KNeighborsClassifier from sklearn for prediction.
Evaluation: Computes accuracy and precision on the test set.




Model Performance

Model Used: K-Nearest Neighbors (k=3)
Accuracy: 98.80%
Precision: 98.83% (Weighted)



How to run: 

This script is optimized for use in Google Colab (uses drive.mount). You may remove or comment out the drive.mount line , if you're running locally
Go to the Runtime section and run all 
