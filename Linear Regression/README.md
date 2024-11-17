- [Introduction](#introduction)
  - [Simple Linear Regression](#simple-linear-regression)
  - [Multiple linear regression](#multiple-linear-regression)
      - [Best Fit Line](#best-fit-line)
      - [Loss Function for Linear Regression](#loss-function-for-linear-regression)


### Introduction
Linear regression is a supervised machine-learning algorithm, that attempts to model the relationship between the dependent variable and one or more independent features by fitting a linear equation to observed data. by fitting a linear equation to observed data. For example, a modeler might want to relate the weights of individuals to their heights (and/or age) using a linear regression model.
Linear regression can also involve one variable (simple linear regression) or several variables (multiple linear regression) or be adapted for yes/no questions (logistic regression). When there is only one dependent variable, it is considered Univariate Linear Regression, while when there are more than one dependent variables, it is known as Multivariate Regression.
Linear regression fits a straight line or surface that minimizes the discrepancies between predicted and actual output values. 
Linear-regression models are relatively simple and provide an easy-to-interpret mathematical formula that can generate predictions. Linear regression can be applied to various areas in business and academic study. Because linear regression is a long-established statistical procedure, the properties of linear-regression models are well understood and can be trained very quickly.

#### Simple Linear Regression
Simple Linear Regression
This is the simplest form of linear regression, and it involves only one independent variable and one dependent variable. The equation for simple linear regression is:
Y = β<sub>0</sub> + β<sub>1</sub>*X + ε

where:
Y is the dependent variable
X is the independent variable
β<sub>0</sub> is the intercept
β<sub>1</sub> is the slope
ε is the error term or the residual term

Slope and inetrcept are also called the coefficients.

![Simple Linear Regression](image.png)


#### Multiple linear regression
In multiple linear regression analysis, the dataset contains one dependent variable and multiple independent variables. The linear regression line function changes to include more factors as follows:

Y= β<sub>0</sub>*X<sub>0</sub> + β<sub>1</sub>*X<sub>1</sub> + β<sub>2</sub>*X<sub>2</sub> + ... + β<sub>n</sub> + ε 

Y is the dependent variable
X<sub>0</sub>, X<sub>1</sub>, X<sub>2</sub>, X<sub>n-1</sub> are the independent variables
β<sub>0</sub>, β<sub>1</sub>, β<sub>2</sub>, β<sub>n </sub> are the coefficients
ε is the residual/error term

###### Best Fit Line
In simple terms, the best-fit line is a line that best fits the given scatter plot. Mathematically, you obtain the best-fit line by minimizing the Residual Sum of Squares (RSS). Linear Regression aims at finding the best values for the coefficients to find the Best Fit Line.

###### Loss Function for Linear Regression
The loss function helps to quantify how good the model works. 