# Sparkify User Churn Prediction

## Overview
This project is the final part of Udacity Data Science Nano-degree . In this project, I will build a predictive model to detect users, who will cancel their subscription, before they cancel it to develop maybe offers or advertisement campaigns for them.

## Overview of Files
Data Files
README.md: This readme file which is contain the describtion of this project.
Sparkify.ipynb: Notebook used in Udacity Workspace.
mini_sparkify_event_data.json: Data file.


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

## References
1- Course material at Udacity has been used for reference.          
2- pySpark documentation:  https://spark.apache.org/docs/latest/api/python/index.html 
