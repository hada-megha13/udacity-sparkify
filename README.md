# udacity-sparkify

Project Motivation

This is the final project of Udacity's Data Scientist Nanodegree program that ask us to predict user churn. This project is based on the Big data using Spark with Python. The full dataset is 12GB, of which a subset was provided by Udacity in the workspace. Also, there is an option to choose Spark cluster on the cloud using AWS or IBM Cloud to analyze full dataset.

Problem Statement

The problem statement of this project is to predict the user churn for an app called Sparkify that allows user to listen to different artists by applying machine learning algorithms.

Libraries Used

Python
Pandas
Matplotlib
Seaborn
PySpark
Spark

Files Description

Sparkify.ipynb is the jupyter notebook which contains exploratory data analysis, feature engineering and modelling steps for the project.

Results

We built and compared two models which are Logistic Regression and Random Forest. First, we trained vanilla structure of both the models and then we used grid search based hyper parameter tuning.
The metric which we measured is F1 Score. Vanilla logistic regression performed better than all the other models and its F1 Score came out to be equal to tuned Random Forest Model i.e of 0.66.
