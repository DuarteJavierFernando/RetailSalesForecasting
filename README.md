# Retail Sales Forecasting 

This project builds a time series forecasting model to predict future sales by store and product category for a retail chain.
I implemented a SARIMA autoregressive model and show the limitations and future improvements of this kind of models.

The goal is to generate accurate demand forecasts to optimize inventory planning and operations for the retail chain.

The project uses historical daily sales data from the Ecuadorian retail chain. You can get the data and more details [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)

I worked on 3 CSV files of data:
- **Base de Datos.csv** : Contains time series of the stores and the product families sales. It combines the data of the "train" and "test" files in the kaggle repo.
- **holidays_events.csv** : Is a meta data. This data is quite valuable to understand past sales, trend and seasonality. It relevance is evaluated here
- **stores.csv** : meta data, gives some information about stores such as city, state, type, cluster.
