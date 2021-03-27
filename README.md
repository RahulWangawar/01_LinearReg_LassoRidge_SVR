# 01_LinearReg_LassoRidge_SVR
In this guide, the focus will be on Regression. Regression models are models which predict a continuous outcome. A few examples include predicting the unemployment levels in a country, sales of a retail store, number of matches a team will win in the baseball league, or number of seats a party will win in an election.

In this guide, you will learn how to implement the following linear regression models using scikit-learn:

Linear Regression
Ridge Regression
Lasso Regression
Elastic Net Regression

++We will evaluate the performance of the model using two metrics - R-squared value and Root Mean Squared Error (RMSE).

   R-squared values range from 0 to 1 and are commonly stated as percentages. It is a statistical measure that represents the proportion of the variance for a target variable that is explained by the independent variables. The other commonly used metric for regression problems is RMSE, that measures the average magnitude of the residuals or error. We will be using both these metrics to evaluate the model performance.

  Ideally, lower RMSE and higher R-squared values are indicative of a good model.
  
  
@ Linear Regression
The simplest form of regression is the linear regression, which assumes that the predictors have a linear relationship with the target variable. The input variables are assumed to have a Gaussian distribution. Another assumption is that the predictors are not highly correlated with each other (a problem called multi-collinearity).

The linear regression equation can be expressed in the following form:

y = a1x1 + a2x2 + a3x3 + ..... + anxn + b

Where the following is true:

y is the target variable.
x1, x2, x3,...xn are the features.
a1, a2, a3,..., an are the coefficients.
b is the parameter of the model.
The parameters a and b of the model are selected through the Ordinary least squares (OLS) method. It works by minimizing the sum of squares of residuals (actual value - predicted value).

In order to fit the linear regression model, step 1) Instantiate the algorithm.    step 2) Fit the model on the training set

   Once the model is built on the training set, we can make the predictions. 
