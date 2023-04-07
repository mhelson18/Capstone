# UsedHondaPricePredictions

# Overview
Used Honda Vehicles Data Analysis
This project is focused on analyzing a dataset containing information on used Honda vehicles, with a specific focus on using mileage to predict the price of the vehicles. The dataset contains the following features:

# What is in the repository? 

The repository contains README file, a jupyter notebook, a project proposal, a dataset, and a project presentation. 
  README File contains: High level overview of the assignment 
  Jupyter notebook contains: Code used to complete the project 
  Project Proposal contains: Proporsed approach to the project 
  Dataset contains: The data collected on Used Hondas 
  Project Presentation: A PDF slidedeck
  
# Which packages were used? 
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost

# Business Understanding 

# Current Situation 
CarWax is a used car dealership that is wanting to expand their product line to include the sale of used Hondas. CarWax would like to increase their profit margin and would like to develop a more strategic approach to purchasing their inventory. 

# What can we do? 

We can use data models to understand the relationship between certain attributes of cars and their sales price. CarWax can use the insights from the analysis to select an optimal price to purchase and resell vehicles at to maximize their profit margin. Purching inventory at an appropriate price will help CarWax successfully expand their product line to include Hondas. 

# How are we doing it? 
Data has been collected on the attributes of Used Hondas and the sales price that will be analyzed for the results we need. 


# Data understanding 

Columns include : 

Year: The year the vehicle was manufactured
Model: The model of the vehicle
Miles: The mileage of the vehicle
Fuel Type: The type of fuel the vehicle uses (Gas or Diesel)
Price (USD): The price of the vehicle in US dollars
Getting Started
To get started with this project, you will need to have the following libraries installed:



# Exploratory Data Analysis

Steps taken for exploring the data: 
Creating a histogram of the prices to visualize the distribution of prices
Using the log transformation to correct the skewness of the Price data
Creating a bar plot to show the count of fuel type values
Creating a scatter plot of the miles vs. price to visualize the relationship between these two features
Building Models
After completing the exploratory data analysis, the next step is to build models to predict the price of a vehicle based on its mileage.

# Data Models 

Linear Regression Model: This model is built using scikit-learn's LinearRegression algorithm. The model is trained on the training data, and the RMSE, R2, and MAE values are calculated using the test data.
RSME: $3012, MAE: $2260 R2: 19%

XGBoost Model: This model is built using XGBoost's XGBRegressor algorithm. The model is trained on the training data, and the RMSE, R2, and MAE values are calculated using the test data.
RSME: $3105, MAE: $2250 R2: 16%

# Recommendation 

CarWax should continue to train the Linear Regression Model. 
More Data should be collected on Used Hondas. 
Deeper analysis of the relationships between different attributes and sales price should be conducted. 
CarWax should integratet the data driven insights into their strategic profit strategy. 

# Conclusion 
This Linear regression model demonstrates how exploratory data analysis and machine learning techniques can be used to analyze a dataset of used Honda vehicles and predict the price of a vehicle based on its mileage. The results of the linear regression and XGBoost models are presented, and future work could include exploring other machine learning algorithms and features in the dataset to improve the accuracy of the predictions.
