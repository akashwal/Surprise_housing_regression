# House Price Prediction
> Objective is to build a required model that predict the Price of the house with the available independent variables. It will be used by the management to understand how the sale price vary with different features. Based on the model prediction/ demand understand, the stretegy will be manipulated to meet the demand levels and meet the customer's expectations. The most fit model will be further way for understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Analysis Involved](#analysis-involved)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
- Dataset of house properties and it's sale price details from the company
- The objective is to predict the sale price on the house and identify the variables
- train.csv (House property data)

## Technologies Used
- seaborn 
- pandas 
- matplotlib 
- numpy 
- statsmodels 
- scikit-learn 
- statsmodels 

## Analysis Involved
- Exploratory data analysis
- RFE regression: model2 building and it's evaluation
- ridge regression: model3 building and it's evaluation
- lasso regression: model4 building and it's evaluation
- Regularization: values coeff's analysis
- GridSearchCV: alpha value finding

## Conclusions
These features are the best variables that explains the SalePrice of the house.<br>
So, The company can focus on these variables on priority.<br>
>1. GrLivArea - Living area is the strongest predictor
>2. Neighborhood_StoneBr - Stone Brook area with Ames city is one of the strong predictor
>3. BsmtFinSF1 - Type 1 finished square feet is the second strongest predictor
>4. GarageArea - Size of garage is one of the strong predictor
>5. KitchenQual - Kitchen quality is one of the strong predictor

Best Alpha values:
- Ridge: 4.51
- Lasso: 0.0001

## Contact
Created by Akash Agrawal
