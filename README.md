# Model Selection and Cross Validation using R. 

I used the regsubsets() function in R to find the best subset selection in order to choose the best model that predicts "Balance" using other variables (in the data) as predictors.  Obtained plots for Cp, BIC, and adjusted R-squared. Found the coefficients of the best model obtained from each. Repeated process using forward step-wise selection.

Part 2: I split the data set into a training set containing 200 observations and a test set containing 200 observations. Then I fit a linear regression of the best four variables model found in the first part. Then computed the estimated test MSE for the linear regression fit. Repeated process using leave-one-out cross-validation and K-FOLD.
