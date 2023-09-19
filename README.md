# Advanced Regression Assignment

> This project uses Regularization to build a polynomial regression model for the prediction of the actual value of the prospective properties and decide whether to invest in them or not.
> - Which variables are significant in predicting the price of a house
> - How well the variables describe the price of a house
>

## Table of Contents
* [General Information](#general-information)
* [Conclusions](#conclusions)

  
## General Information

- **General information:** 

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- **Background:** 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

- **Business problem:**
Aim is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Assignment Steps performed in the notebook

## Data visualisations
- perform EDA to understand various variables
- check correlation between the variables 

## Data preparation
- clean the data structure
- drop unneccessary variables
- create dummy variables for all categorical features
- divide the data to train and test
- perform scaling
- divide data into dependent and independent variables

## Data modelling and evaluation
- create linear regression model with no Regularization
- create models using Ridge and Lasso Regularization
- report the final model

## Conclusions
Please see the notebook for more detailed insights.
Lasso is the chosen model for the final model, because it creates a simple model with the top features.
