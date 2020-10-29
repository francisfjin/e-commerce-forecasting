# E-Commerce: Value Prediction and Time-series Forecasting
![](https://github.com/francisfjin/e-commerce-forecasting/blob/main/ecommerce.jpeg)

This project conducts Value Prediction and time-series forecasting to analyze e-commerce data to analyze trends in revenue and marketing effectiveness for a large-scale online retailer. 

Main script [here](https://github.com/francisfjin/e-commerce-forecasting/blob/main/final.ipynb).

Final report [here]( ).

## Data

Datasets are published on Kaggle by Olist, the largest department store retailer in Brazil. 

[E-commerce dataset](https://www.kaggle.com/olistbr/brazilian-ecommerce)

[Marketing datatset](https://www.kaggle.com/olistbr/marketing-funnel-olist)

## Exploratory Data Analysis and Feature Selection

Target variable revenue is investigated by time-series and grouped by seller and product category. 

![](https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/timeseries.png)

![](https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/monthly.png)

![](https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/autocorr.png)

Features for the dataset are listed on Kaggle [here](https://www.kaggle.com/olistbr/brazilian-ecommerce) and [here](https://www.kaggle.com/olistbr/marketing-funnel-olist).

## Models

[Sklearn linear regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)

[Keras neural networks](https://keras.io/)

![](https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/neuralnet.png)

[Facebook Prophet](https://facebook.github.io/prophet/) is used as well for time-series forecasting. It is a forecasting procedure made by Facebook's Core Data Science team, based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It can be installed [here](https://pypi.org/project/fbprophet/)



