# REGRESSION

Regression analysis produces an equation to describe the relationships between a set of independent variables and the dependent variable. With the help of this equation we can predict the value of dependent variable.

types of regression analysis:

# 1. Linear Regression 
![linear regression](https://user-images.githubusercontent.com/58341480/93008886-bf812480-f597-11ea-9700-a8f7cebf6c21.png)

## Simple Linear Regression
* Predictions are made using one independent variable
* It is assumed there is a linear relationship between dependent and independent variables.
* We shall try to find the best fit line that represents the linear function.
* The equation of the best fit line has the form Y= a + bX
  - Y - dependent variable
  - X - independent variable
  - a - y intercept
        
* Steps:
  - Data Preprocessing
  - Building a model on training dataset
  - Predicting the result
  - Visualization
    
## Multiple Linear Regression
* Predictions are made using two or more independent variables
* It is similar to simple linear regression model, where it is assumed
  - Linearity:
    The relationship between dependent and independent variable should be linear
  - Homoscadasticity
    Constant variance
  - Multivariate Normality
    the residuals are normally distributed
  - Multicollinearity
  Little or no multicollinearity is assumed 
* We shall try to find the best fit line that represents the linear function.
* The equation of the best fit line has the form y = b1x1 + b2x2 + … + bnxn + c.
  - Y - dependent variable
  - X - independent variable
  - a - y intercept
