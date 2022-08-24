## Linear Regression from Scratch <hr>

<p align="center">
  <a href="https://github.com/rppradhan08/ml-models-from-scratch/tree/main/1.%20Linear%20Regression">
    <img src="https://github.com/rppradhan08/ml-models-from-scratch/blob/main/1.%20Linear%20Regression/lr_train.gif?raw=true" alt="Logo" width="500" align="center">
  </a>
</p>

In statistics, linear regression is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables (also known as dependent and independent variables). The case of one explanatory variable is called simple linear regression; for more than one, the process is called multiple linear regression. This term is distinct from multivariate linear regression, where multiple correlated dependent variables are predicted, rather than a single scalar variable.

In this module we will build a custom linear regression model from scratch using numpy. Below is the brief layout of the `LinearRegression` class i.e. being used in this module.

    LinearRegression
        |
        |--fit() : This method is used to train the model.
        |
        |--cost_function() : This function uses OLS method to calculate cost.
        |
        |--predict() : This generates estimate for the given input.
