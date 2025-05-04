# NeuroNexus
Doing Titanic Survival Prediction Project as a part of my NeuroNexus Internship 

# Titanic Survival Prediction Project

This project is a *Data Science and Machine Learning* project to predict the survival of passengers in the Titanic disaster using the Titanic dataset from Kaggle.  
The project includes *Data Cleaning, **Exploratory Data Analysis (EDA), and a **Logistic Regression classification model*.

## Dataset

The dataset is taken from the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data) competition on Kaggle.

- train.csv: Contains training data with features and target variable (Survived)

## Problem Statement

Predict whether a passenger survived the Titanic shipwreck based on features such as age, gender, class, etc.

## Tools & Libraries Used

- Python
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit-learn

## Project Steps

### 1. Data Cleaning

- Handled missing values in Age and Embarked columns
- Dropped the Cabin column due to high missing values

### 2. Exploratory Data Analysis (EDA)

- Explored relationships between features and survival
- Visualized survival distribution by gender, class, and age

### 3. Feature Engineering

- Converted categorical features (Sex, Embarked) into numerical variables using one-hot encoding
- Dropped unnecessary columns (Name, Ticket, PassengerId)

### 4. Model Building

- Split data into training and test sets
- Trained a *Logistic Regression* model to predict survival

### 5. Model Evaluation

- Evaluated model performance using accuracy, confusion matrix, and classification report

## Model Performance

- *Accuracy* achieved: ~ (Add your final accuracy here after running the notebook)
