Titanic Survival Prediction (Beginner ML Project)

This is a machine learning classification project using the famous Titanic dataset. The goal is to predict whether a passenger survived the Titanic disaster based on features like age, sex, ticket class, and more.

Dataset
 Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
 Files used: train.csv (main dataset)
           : test.csv

Tools & Libraries Used
 Python
 Pandas
 NumPy
 Seaborn & Matplotlib
 Scikit-learn (Logistic Regression)

Data Cleaning
 Filled missing Age values with the median
 Filled missing Embarked values with the mode
 Dropped the Cabin column (too many missing values)
 Converted categorical features (Sex, Embarked) into numerical values

Features Used
 Pclass: Ticket class
 Sex: Gender (converted to 0/1)
 Age
 SibSp: no of siblings/spouses aboard
 Parch: no of parents/children aboard
 Fare
 Embarked: Port of embarkation (encoded)

Model Used
 Logistic Regression
   Trained using 80% of the data
   Tested on remaining 20%
   Evaluated with accuracy and classification report

Key Results
 The model achieved decent accuracy predicting survival
 Gender had a strong influence on survival
 1st class passengers had higher chances of survival

Future Improvements
 Try other models (Random Forest, SVM)
 Handle outliers in Fare or Age
 Engineer new features like Title from the Name



Made by FAS
