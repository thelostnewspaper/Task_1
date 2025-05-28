# Task_1
elevate labs task 1
   

This repository contains a Python script that performs data cleaning and preprocessing on the Titanic dataset. The goal is to prepare the raw data for machine learning tasks by handling missing values, encoding categorical variables, scaling numerical features, and providing basic data visualization.    

Dataset
   

The dataset used is the Titanic passenger data (train.csv), which contains information about passengers such as their age, sex, fare, cabin, embarkation point, and survival status.    

Features of the Preprocessing Script
   

Missing Value Handling:

Fills missing values in the 'Age' column with the median age.
Fills missing values in the 'Embarked' column using the mode (most common value).
Drops the 'Cabin' column due to excessive missing data.    
Categorical Encoding:

Converts the 'Sex' column from categorical text to numeric labels.
Applies one-hot encoding to the 'Embarked' column.    
Feature Scaling:

Uses StandardScaler to normalize numerical features: Age, Fare, SibSp (siblings/spouses aboard), and Parch (parents/children aboard).    
Data Cleaning:

Drops columns that are not relevant for modeling (PassengerId, Name, Ticket).    
Visualization:

Includes histograms with KDE plots for the scaled Age and Fare features to inspect distributions after scaling.    
How to Use
   

Upload the train.csv dataset to your working directory or Google Colab environment.
Run the provided Python script (data_cleaning_preprocessing.py) to perform the cleaning and preprocessing steps.
The script outputs:
A cleaned and preprocessed dataset saved as titanic_cleaned.csv.
Visualizations of the distributions of Age and Fare features after scaling.    
Requirements
   

Python 3.x
pandas
numpy
seaborn
matplotlib
scikit-learn
