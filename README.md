# This Repository contains several Notebooks associated with articles


**01_regression_xgboost.ipynb:** A regression model is trained predicting house prices for King County using XGBoost. 
The data can be found on [Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction). 
After some preprocessing the model is fit using mean squared error already implemented in the XGBoost package.


## Loss Functions in XGBoost and how to customize them
This notebook contains an explanation how to customize loss function using XGBoost. The article can be found on [medium](https://medium.com/@falbrechtg/loss-functions-in-xgboost-c89885b57346)

**02_custom_loss_xgboost.ipynb:** The model from the first notebook is used to explore different loss functions. 
It is explained how we customize the loss in XGBoost showing several examples.

![different_losses](compare_loss_train.jpg)
*The effect of different loss functions*

## Getting started with mlflow Experiment tracking - using a local folder and sqlite
**03_mlflow.ipynb:** In this notebook we learn how to use mlflow or experiment tracking, when results are stored in a local folder or a sqlite database. The article can be found on [medium](https://medium.com/@falbrechtg/getting-started-with-mlflow-tracking-46a0089d6a73)

## Easy analyze your Data and ML model using Evidently AI
**04_evidently.ipynb:** In this notebook we consider the regression problem of predicting house prices and explore how we can use Evidently AI dashboards and profiles to monitor our data and model. 
