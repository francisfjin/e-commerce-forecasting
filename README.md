# E-Commerce: Value Prediction and Time-Series Forecasting

<img src="https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/ecommerce.png" height="300" width="450">

This project conducts Value Prediction and time-series forecasting on e-commerce data to analyze trends in revenue and marketing funnel effectiveness for a large-scale online retailer. **Check it out on the [website!](https://francisfjin.github.io/e-commerce-forecasting/)**

Specifically answering the following questions: 
- Can we detect any patterns in revenue sources either by seller, product type, or location? 
- What factors from our marketing funnel have the biggest impact on a seller's revenue? 
- Can we use this information to accurate predict revenue given time-series data? 

Main script [here](https://github.com/francisfjin/e-commerce-forecasting/blob/main/final.ipynb).

Final report [here]( ).

## Data

Datasets are published on Kaggle by Olist, the largest department store retailer in Brazil.

[E-commerce dataset](https://www.kaggle.com/olistbr/brazilian-ecommerce)

The e-commerce dataset is real and anonymized commercial data containing over 100,000 orders executed on Olist’s site from 2016 to 2018. Features include: order status, price, payment, delivery, freight performance, customer location, product attributes, reviews, and seller geolocation data. 

[Marketing datatset](https://www.kaggle.com/olistbr/marketing-funnel-olist)

The marketing dataset is from the marketing funnel of sellers that filled-in requests to sell products on Olist. The dataset has information on 8,000 marketing qualified leads from 2017 to 2018, as well as features describing the deals that were closed. Features include: lead type, lead behavior profile, lead category, catalog size, business type, average stock, sales representative, date the deal was closed, origin of the lead. 

## Models

[Sklearn linear regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)

[Keras neural networks](https://keras.io/)

<img src="https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/neuralnet.png" height="400" width="600">

[Facebook Prophet](https://facebook.github.io/prophet/). It is a forecasting procedure made by Facebook's Core Data Science team, based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It can be installed [here.](https://pypi.org/project/fbprophet/)

<img src="https://github.com/francisfjin/e-commerce-forecasting/blob/main/images/prophet.png" height="400" width="650">




