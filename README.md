# Advanced Linear Regression
## House Price Prediction Case Study

#### Problem Statement:

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

### Steps 
1.	EDA
    1. Data Cleaning
    2. Data Preparation
    3. Data Analysis
2.	Multiple Linear Regression 
    1. Model Building
    2. Model Evaluation
3.	Lasso Regression with alpha as 0.01 
4.	Ridge Regression with alpha as 2 
5.	For Subjective Question 1 :- Ridge and Lasso after we double the alpha
6.	For Subjective Question 3 :-  Removing five most important predictor variables in the lasso model and checking the impact
    
### Conclusions :-
**1. The variables that are significant in predicting the house prices are :-**
  1.  As per Multiple Linear regression top five variables are
      - YearBuilt, TotalBsmtSF, 2ndFlrSF, GrLivArea, Exterior2nd_Stucco
  3.  As per Lasso regression top five variables are
      - GrLivArea, GarageArea, OverallQual_OQVGood, Foundation_PConc, BsmtFinType1_GLQ
  4.  As per Ridge regression top five variables are
      - GrLivArea, 1stFlrSF, OverallQual_OQExcellent, 2ndFlrSF, TotalBsmtSF

### About Repository (Files) -
1. Python File for assignment named as "Advanced Regression Assignment.ipynb"
2. PDF File for Subjective questions with answers.

### Contact
Created by **[@TruptiUD]**
