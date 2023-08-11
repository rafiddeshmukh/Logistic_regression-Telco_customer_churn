# Logistic_regression-Telco_customer_churn
To predict the whether a customer will churn or not, based on the variables available in the Telco customer churn data.

![image](https://github.com/rafiddeshmukh/Logistic_regression-Telco_customer_churn/assets/52603382/50469907-8563-4d5e-bc95-e9695d695e38)


## Objective
------

To predict the whether a customer will churn or not, based on the variables available in the Telco customer churn data.
Logistic regression does not make many of the key assumptions of linear regression and general linear models that are based on ordinary least squares algorithms – particularly regarding linearity, normality, homoscedasticity, and measurement level.
First, logistic regression does not require a linear relationship between the dependent and independent variables. Second, the error terms (residuals) do not need to be normally distributed. Third, homoscedasticity is not required. Finally, the dependent variable in logistic regression is not measured on an interval or ratio scale.
However, some other assumptions still apply.
First, binary logistic regression requires the dependent variable to be binary and ordinal logistic regression requires the dependent variable to be ordinal.
Second, logistic regression requires the observations to be independent of each other. In other words, the observations should not come from repeated measurements or matched data.
Third, logistic regression requires there to be little or no multicollinearity among the independent variables. This means that the independent variables should not be too highly correlated with each other.
Fourth, logistic regression assumes linearity of independent variables and log odds. although this analysis does not require the dependent and independent variables to be related linearly, it requires that the independent variables are linearly related to the log odds.


### In this assignment, you need to do the following :
* Remove correlated variables and run Logistic Regression
* Also implement regularized logistic regression using the hyperparameter C in the sklearn implementation. Add details about how this hyperparameter affects the learning and performance of the model.
* Evaluate your logistic regression models using metrics such as roc_auc, log_loss, precision, recall, accuracy and f-score. You already know these metrics from your assignments in Module 1. Explain your observations about these metrics results
