
# Wine color prediction

[**List of Contents**](#list-of-Contents)
  - [Overview](#overview)
  - [Directory structure](#directory-structure)
  - [About the Dataset](#about-the-Dataset)
  - [Directory Structure](#Directory-Structure)
  - [Libraries Used](#Libraries-Used)
  - [Steps performed](#Steps-performed)
## Overview

The problem statement is regarding wine color prediction.

Supervised classification Machine Learning models have been built to perform the binary classification between white and red wines.
## About the Dataset

Link: https://www.kaggle.com/datasets/saigeethac/red-and-white-wine-quality-datasets?select=winequality-white.csv

Abstract: Two datasets are included, related to red and white vinho verde wine samples, from the north of Portugal. The goal is to model wine quality based on physicochemical tests.

Data Set Information:
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine.

Attribute Information:
Variables (based on physicochemical tests):

- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality (score between 0 and 10)
- color (red and white)
## Directory structure

The code is stored as a jupyter notebook **Wine_color_prediction.ipynb**
## Libraries Used

The libraries that we used to build this project are:

 #### numpy
  ![numpy](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Numpy.png?raw=true)
 #### pandas
 ![pandas](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Pandas.png?raw=true)
 #### matplotlib
 ![matplotlib](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Matplotlib.png?raw=true)
 #### seaborn
 ![seaborn](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Seaborn.png?raw=true)
 #### sklearn
 ![skleanr](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Sklearn.png?raw=true)
## Steps performed

- Downloaded the dataset
- Read the dataset as a dataframe
- Exploratory Data Analysis
- Data Preprocessing and data cleaning
- Feature Engineering
- Feature importance
- Feature selection
- Feature scaling
- Model Building
- Model training
- Model testing
- Model evaluation
- Hyperparameter tuning
## Model Performance

MODEL PERFORMANCE: 

- The Logistic Regression model is yielding an accuracy score of 99.29% along with recall and precision scores of 0.99 and 0.99 respectively on the test data.

- The DecisionTreeClassifier model is yielding an accuracy of 96.82% along with recall and precision scores of 0.96 and 0.96 respectively on the test data.

- The Gaussian Naive Bayes model is yielding an accuracy of 98.76% along with recall and precision scores of 0.98 and 0.99 on the test data.

- The KNeighborsClassifier model is yielding an accuracy of 99.47% along with recall and precision scores of 0.99 and 0.99 respectively on the test data.

- The RandomForestClassifier model is yielding an accuracy of 98.76% along with recall and precision scores of 0.98 and 0.99 respectively on the test data.

- The SVM model is yielding an accuracy score of 99.47% along with recall and precision scores of 0.99 and 0.99 respectively on the test data.

- The hyperparameter tuned Logistic Regression model with argument penalty = l2 and C=10 is yielding an accuracy score of 98.94% on the test data.

- The hyperparameter tuned RandomForestClassifier model is yielding an accuracy score of 98.41% on the test data.