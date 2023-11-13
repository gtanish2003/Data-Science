# Simple Linear Regression with OLS Method

## Introduction

Simple linear regression is a statistical method that models the relationship between two variables by fitting a straight line to the observed data. The method assumes that the relationship between the two variables is linear and that there is no error in the independent variable.

## Ordinary Least Squares (OLS)

Ordinary least squares (OLS) is a method for fitting a line to data by minimizing the sum of the squared residuals. The residuals are the differences between the observed values of the dependent variable and the values predicted by the fitted line.

## Formulae

The formula for simple linear regression using the OLS method is:


ŷ = mx + b
where:

ŷ is the predicted value of the dependent variable
x is the independent variable
m is the slope of the line
b is the y-intercept


The slope of the line is calculated by
    m = Σ[(xi - x̄)(yi - ȳ)] / Σ(xi - x̄)²

where:
xi is the ith observation of the independent variable
x̄ is the mean of the independent variable
yi is the ith observation of the dependent variable
ȳ is the mean of the dependent variable


The y-intercept of the line is calculated by:
    b = ȳ - mx̄


## Regression Metrics

Regression metrics are used to evaluate the performance of a regression model. Some common regression metrics include:

* Mean absolute error (MAE): The MAE is the average of the absolute differences between the observed values of the dependent variable and the values predicted by the fitted line.


    MAE = 1/n Σ|yi - ŷi|


* Mean squared error (MSE): The MSE is the average of the squared differences between the observed values of the dependent variable and the values predicted by the fitted line.

    MSE = 1/n Σ(yi - ŷi)²

    RMSE = √MSE


* R-squared: The R-squared is the proportion of the variance in the dependent variable that is explained by the independent variable.


    R² = 1 - Σ(yi - ŷi)² / Σ(yi - ȳ)²




## Conclusion

Simple linear regression is a powerful tool for modeling the relationship between two variables. The OLS method is a common method for fitting a line to data. Regression metrics can be used to evaluate the performance of a regression model.

