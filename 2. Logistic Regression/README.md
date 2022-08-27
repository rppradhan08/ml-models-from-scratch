## Logistic Regression from Scratch <hr>

<p align="center">
  <a href="https://github.com/rppradhan08/ml-models-from-scratch/tree/main/2.%20Logistic%20Regression">
    <img src="https://github.com/rppradhan08/ml-models-from-scratch/blob/main/2.%20Logistic%20Regression/images/confusion%20matrix.png?raw=true" alt="Logo" width="500" align="center">
  </a>
</p>

In statistics, the (binary) logistic model (or logit model) is a statistical model that models the probability of one event (out of two alternatives) taking place by having the log-odds (the logarithm of the odds) for the event be a linear combination of one or more independent variables ("predictors"). In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (the coefficients in the linear combination). Formally, in binary logistic regression there is a single binary dependent variable, coded by a indicator variable, where the two values are labeled "0" and "1", while the independent variables can each be a binary variable (two classes, coded by an indicator variable) or a continuous variable (any real value). The corresponding probability of the value labeled "1" can vary between 0 (certainly the value "0") and 1 (certainly the value "1"), hence the labeling; the function that converts log-odds to probability is the logistic function, hence the name. The unit of measurement for the log-odds scale is called a logit, from logistic unit, hence the alternative names.

In this module we will build a custom Logistic regression model from scratch using numpy. Below is the brief layout of the `LogisticRegression` class i.e. being used in this module.

    LogisticRegression
        |
        |--fit() : This method is used to train the model.
        |
        |--cost_function() : This function uses Binary-CE method to calculate cost.
        |
        |--predict() : This generates estimate for the given input.
