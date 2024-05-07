## Introduction

Welcome to the Titanic Survival Prediction Notebook!

In this Jupyter notebook, we'll explore the famous Titanic dataset from the Kaggle competition "Titanic: Machine Learning from Disaster." The goal of this project is to predict whether a passenger survived the sinking of the Titanic based on various features such as age, gender, ticket class, and more.

The sinking of the RMS Titanic on April 15, 1912, remains one of the deadliest maritime disasters in history. Despite its tragic outcome, the Titanic dataset provides a unique opportunity to apply machine learning techniques to understand patterns of survival and uncover insights into the factors that influenced passengers' chances of survival.

Throughout this notebook, we'll follow a step-by-step process to analyze the dataset, preprocess the data, build predictive models, and evaluate their performance. By the end of this notebook, we aim to develop a predictive model that accurately predicts whether a passenger survived the Titanic disaster.

## 1. Problem Definition
 Is it possible to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## 2. Data
Data taken from the Kaggle Titanic competition. The data has been broken into a training and testing CSV. Data includes information such as the passenger's gender and social class. The final submission will just be a DataFrame that contains the passenger's ID and predicted survival status.

* https://www.kaggle.com/competitions/titanic/data

## 3. Evaluation
My goal for this project is build a model with at least 90% accuracy.


## 4. Features 
Below is a data dictionary explaining all the different data points

|Variable| Definition| Key|
|:-------|:----------|:---|
|survival|Survival|0 = No, 1 = Yes|
|pclass|Ticket class|1 = 1st, 2 = 2nd, 3 = 3rd|
|sex|Sex|
|Age|Age in years|
|sibsp|# of siblings |# of siblings aboard the Titanic|
|parch|# of parents |# of children aboard the Titanic|
|ticket|Ticket number|
|fare|Passenger fare|
|cabin|Cabin number|
|embarked|Port of Embarkation|C = Cherbourg, Q = Queenstown, S = Southampton|

## Link
View the Jupyter notebook [here](https://github.com/mikemiller97/titanic-ml-model/blob/main/titanic-death-prediction-kaggle-link.ipynb) on GitHub to explore the project code and view my results.
