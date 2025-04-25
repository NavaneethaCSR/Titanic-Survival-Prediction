# Titanic-Survival-Prediction

1. The dataset is loaded directly from a public Google Sheets CSV link and selected relevant feature  and target variable about Titanic passengers such as:

Pclass- Socio-economic class (1st, 2nd, 3rd) is highly predictive.

Sex-Gender is very important (e.g., more women survived).

Age- Children were more likely to survive; they needed handling for missing values.

SibSp- indicates family on board; impacts survival (somewhat correlated with Age)

Parch-Like SibSp — more family = possibly better survival or group effect

Fare- Can indicate wealth/class; moderately useful.

Embarked- Weak predictor alone, but still helps a bit (C, Q, S had different survival rates)

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
In colab
1.This script is optimized for use in Google Colab,so upload the dataset and  uses drive.mount. 
2.Go to the Runtime section and run all.

If running locally:
1.Install neccessraty packages using pip install
2.You may remove or comment out the drive.mount line , if you're running locally

 
