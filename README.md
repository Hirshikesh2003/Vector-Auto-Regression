# Vector-Auto-Regression

Vector Autoregression (VAR) is a statistical model used to analyze the relationships between multiple time series variables. It is an extension of the autoregressive model (AR) to multiple variables. In a VAR model, each variable in the system is regressed on its own lagged values and the lagged values of all other variables in the system.

The VAR model assumes that the behavior of each variable is influenced by its own past values as well as the past values of other variables in the system. It captures the interdependencies and feedback effects among the variables, allowing for a more comprehensive analysis of their dynamics.

It can be used for various purposes, including forecasting future values of the variables, studying impulse response functions to shocks, and conducting Granger causality tests to analyze causal relationships between the variables.

A Vector Autoregression (VAR) model is a multivariate time series model that captures the dynamics and interdependencies among multiple variables by regressing each variable on its own lagged values and the lagged values of all other variables in the system.

In this project, we have used the VAR model to predict a variable called "CPI". The dataset is Walmart sales dataset taken from Kaggle. I have sorted the dataset to have only the sales data of the first store.

Using Temperature and Fuel Price as the independent variables and the VAR model I tried to analyze the relationship between the independent variables to CPI.

Using the VAR model the final equation that corresponds to the lags and co-efficient is;

![image](https://github.com/Hirshikesh2003/Vector-Auto-Regression/assets/78225619/52965a4a-9d75-4239-8fea-0bb7a1a0a05f)

# VARMAX Model

Later in this project, the VARMAX model is used and the predictions are plotted.

![image](https://github.com/Hirshikesh2003/Vector-Auto-Regression/assets/78225619/8df92455-9b76-46b2-b38b-16a91bfa298f)

We can see that the predicted output has almost formed an understanding shape, but is not that accurate, this is mainly due to the dataset size. Increasing the data the model might perform well.

