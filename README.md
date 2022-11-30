# Advanced Regression Assignment 
House price prediction


## Table of Contents
* [General Info]
* [Technologies Used]
* [Steps Used]
* [Conclusions]
* [Acknowledgements]


## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia.
The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. 
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

Business Goal :
You are required to model the price of houses with the available independent variables. 
This model will then be used by the management to understand how exactly the prices vary with the variables.
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Technologies Used
Libraries used
numpy 
pandas
matplotlib
seaborn 
%matplotlib inline 
MinMaxScaler
sklearn.feature_selection
sklearn.linear_model LinearRegression
statsmodels.stats.outliers_influencevariance_inflation_factor
statsmodels.stats.outliers_influence 
sklearn.linear_model import Ridge
sklearn.linear_model import Lasso
sklearn.model_selection import GridSearchCV
sklearn.metrics import r2_score
sklearn.model_selection import KFold

## Steps Used
1. Reading and Understaning the data
2. Data Quality Check 
3. Data Preparation - Missing value treatment
4. Data imputation for  Catagorical columns
5. Data imputation for  Numeric columns
6. Removing redundant & unwanted columns
7. univariate analysis on Numeric columns
8. Bivariate analysis
9. Visualising Catagorical Variables
10. Data Preprocessing - Tranforming the Target variable(SalePrice)
11. Creating Dummy Variables
12. Splitting the Data into Training and Testing Sets¶
13. Rescaling the features
14. RFE(Recursive feature elimination):
15. Building Linear Model using 'STATS MODEL'
16. Data Modeling - Advanced Regression
17. Ridge Regression
18. Lasso regression
19. Data Modeling and evaluation - Final model
20. Final report


## Conclusions

As per our final Model, the top 10 predictor variables that influences the price of a house:


1. LotFrontage : If the house Linear feet of street connected to property area increase then the Price increase.

2. BsmtFullBath : : If the BsmtFullBath area is more the SalePrice is higher

3. OverallCond(Overall Condition): If the Overall Condition is Excellent the SalePrice is higher.

4. Exterior1st_BrkFace : IF the house Exterior1st is Brick Face then price is less.

5. OverallQual(Overall quality): If the Overall quality is Excellent the SalePrice is higher

6. MSZoning_RH(RH= Residential High Density) : If the house is near residential area then the SalePrice is higher

7. CentralAir: If the CentralAir is Yes the SalePrice is higher

8. MSZoning_RM (RM=Residential Medium Density)	: If the house is near residential area then the SalePrice is higher

9. Street_Pave: if the road access to property is pave then SalePrice is higher

10. GarageArea: If the Garage area is high the SalePrice is higher


Optimal value of alpha:

For Ridge regression :1.0
For Lasso Regression :0.0001

## Acknowledgements


## Contact
Created by Bindu GK  

