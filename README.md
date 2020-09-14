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
* Steps:
  - Data Preprocessing
  - Building a model on training dataset
  - Predicting the result
  - Evaluation
  
## Support Vector Regression
![SVR regression](https://user-images.githubusercontent.com/58341480/93008890-c27c1500-f597-11ea-8575-c23ee21d9d4d.png)
* In most linear regression models, the objective is to minimize the sum of squared errors.
* But, SVR gives us the flexibility to define how much error is acceptable in our model and will find an appropriate line (or hyperplane in higher dimensions) to fit the data.
* Instead of minimizing the observed training error, Support Vector Regression (SVR) attempts to minimize the generalization error bound so as to achieve generalized performance.
* The idea of SVR is based on the computation of a linear regression function in a high dimensional feature space where the input data are mapped via a nonlinear function.
        
* Steps:
  - Data Preprocessing
  - Building a model on training dataset
  - Predicting the result
  - Visualization
  
## Decision Tree Regression
![ Decision tree Regression](https://user-images.githubusercontent.com/58341480/93008895-c740c900-f597-11ea-903c-4468d2cad9ca.png)

![example](https://user-images.githubusercontent.com/58341480/93008893-c445d880-f597-11ea-97f1-f277c5ea2728.png)

* It is a type of supervised learning Algorithm
* It is a tree in which each branch node represents a choice between a no.of alternatives and each leaf node represents a decision.
* what it does
  - Cut the data points into slices in several iterations
  - We split the data and construct a decision tree.
  - the tree that is obtained by applying algorithms like CART, ID3 will be used to make the predictions
* Key words
  * Information gain
    - The best attribute is the one which gives us the maximum information gain.
  * Entropy
      - It is a measure of randomness
      - how to compute entropy for dataset:
        1. compute entropy for the data-set
        2. for every feature 
            - calculate entropy for all categorical variables
            - take average information entropy for the current attribute
            - calculate gain for the current attribute
        3. pick the highest gain attribute
        4. repeat until we get the tree we desired
        

## Random Forest Regression
* Random forests are supervised ensemble-learning models used for classification and regression.
* It builds multiple decision trees and merges them together to get a more accurate and stable prediction.
![ensemble learning](https://user-images.githubusercontent.com/58341480/93008894-c5770580-f597-11ea-8e2b-bf65f5ce8f06.png)
* The logic beg=hind this algorithm is that each of the models used is weaked when employed on its own, but once they all are put together they become strong.
* Employing the above logic a large no. of weak decision trees which are weak are aggregated representing the "strong" ensemble
* steps involved
  - Creation of the random forest regressor
  - Make a prediction from the random forest regressor
* The process of finding the root nide and splitting the feature nodes is what makes random forest from decision trees.
