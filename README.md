# Sparkify User Churn Prediction

## Overview
This project is the final part of Udacity Data Science Nano-degree . In this project, I will build a predictive model to detect users, who will cancel their subscription, before they cancel it to develop maybe offers or advertisement campaigns for them.

# Expected Results
At the end of this project, a model for churn prediction should have been created and evaluated. The model should have been trained and tested on a subset of the 12GB of data.

## Overview of Files
Data Files
README.md: This readme file which is contain the describtion of this project.  
Sparkify.ipynb: Notebook used in Udacity Workspace.


## Required installation
The following packages/libraries are required the data loading, preprocessing and machine learning algorithm:

Python
Pyspark
Pandas
Numpy
Matplotlib
Seaborn

## General procedure

First step an exploratory data analysis is carried out to understand the different variables and structure of the dataset. Once the provided information is understood, a churn column is created to use as label for the subsequent model.

With this churn columns, we have continue the EDA to find the optimal features, which can help to understand the behaviour of the churned and non-churned users.

After creating a new dataset with some processed features, a ML model is developed testing different approaches: logistic regression and random forest.
conclusion from the first and last models look promising without great optimization.

## Summary of Project

data cleaning
data exploration
feature engineering
modelling
deploy on IBM cloud 

## Blog post
https://medium.com/@elham.almutairy/sparkify-user-churn-prediction-d088d52d31a2

## Acknowledgement
The dataset is kindly provided by Udacity team. And some instructions in the notebook are also well prepared by Udacity team.

## References
1- Course material at Udacity has been used for reference.          
2- pySpark documentation:  https://spark.apache.org/docs/latest/api/python/index.html 
