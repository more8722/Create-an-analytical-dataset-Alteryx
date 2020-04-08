# Project Overview
This project is the first part of a two-part series. In the first part, you will blend and format data and deal with outliers.
For the second part, you will use your cleaned up dataset to create another linear regression model. The difference this time is that you will have to choose which variable(s) are the most important for the model using new techniques learned in the Selecting Predictor Variables section.
# Scenario
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.
The list of customers that need to be processed in the next few days
# The Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.
Your first step in predicting yearly sales is to first format and blend together data from different datasets and deal with outliers.
Your manager has given you the following information to work with:
The monthly sales data for all of the Pawdacity stores for the year 2010.
NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
A partially parsed data file that can be used for population numbers.
Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in the state of Wyoming. For people who are unfamiliar with the US city system, a state contains counties and counties contains one or more cities.
# For part2 results are directly from Udacity .see below for part2 details :
# Practice Project Overview
This project is a continuation of the Create an Analytical Dataset project regarding trying to find the best city to expand for Pawdacity's newest pet store. It will not be reviewed, but is here to give you some additional practice.
# Scenario
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales
# The Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.
In the first part, you've already cleaned up the dataset and dealt with outliers. 
In this project, you will take this dataset that you cleaned up and use this dataset to train a linear regression model in order to predict sales 
Here are the criterias given to you in choosing the right city:
The new store should be located in a new city. That means there should be no existing stores in the new city.
The total sales for the entire competition in the new city should be less than $500,000
The new city where you want to build your new store must have a population over 4,000 people (based upon the 2014 US Census estimate).
The predicted yearly sales must be over $200,000.
The city chosen has the highest predicted sales from the predicted set.
# Steps to Success
Step 1: Build a Linear Regression Model
Analyze the dataset you created in Project 2.1 and look at the distribution of your data. You can create histograms to look at each of your continuous and categorical data to determine the nature of the data you’re working with.
Important: You should have 10 rows of data before you begin modeling the dataset. The correct answers will assume that you removed Gillette from the dataset. If you decided to remove a different outlier in P2.1, you will have to adjust your dataset for this project.
Build a linear regression model to help you predict total sales.
# Step 2: Perform the Analysis
Use your regression model to calculate predicted sales for all of the cities and use the criteria given to you to make a recommendation.
