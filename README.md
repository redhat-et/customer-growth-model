# Growth Forecasting Model

This project aims to develop accurate customer/user revenue forecasting using [ARIMA](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average) and other time series forecasting ML models to help drive business growth and enable organizations to be more data driven.

In light of the recent advancements in AI, particularly in predictive modeling, we now have a powerful tool at our disposal to quickly consume and analyze vast amounts of data. By using open source time series forecasting ML models such as ARIMA and [Prophet](https://facebook.github.io/prophet/), we can provide more accurate predictions and insights in real-time, enabling organizations and teams to streamline processes and increase efficiency, improve and manage customer risk, and adapt to changing market conditions.

## Time Series Forecasting Models

Time series forecasting models are statistical models that use historical data to predict future values. These models are used in a variety of industries, including finance, retail, and manufacturing.

There are many different types of time series forecasting models, but some of the most common include:

* Autoregressive models (AR): These models use past values of the time series to predict future values.
* Moving average models (MA): These models use past errors in the time series to predict future values.
* Autoregressive moving average models (ARMA): These models combine AR and MA models.
* Seasonal autoregressive integrated moving average models (SARIMA): These models are used for time series that have seasonal patterns.

The choice of which time series forecasting model to use depends on the characteristics of the time series data. For example, if the time series data is very noisy, then a model that is robust to noise, such as an ARMA model, may be a good choice. For this project, we have chosen the ARIMA model.

## Data

To develop these open source models, we are using a public dataset from [Kaggle](https://www.kaggle.com/datasets/census/business-and-industry-reports?select=notes.txt). The data consists of unique account IDs and monthly revenue which we primarily use to train our model. We would also like to use Generative AI techniques to generate public datasets that mimic internal company/business customer revenue data, you can follow [this issue](https://github.com/redhat-et/customer-growth-model/issues/7) to learn more about our progress.

## Repo Structure

* [`data`](https://github.com/redhat-et/customer-growth-model/tree/master/data)
    * [`data/raw`](https://github.com/redhat-et/customer-growth-model/tree/master/data/raw) - directory contains the raw dataset (obtained from Kaggle)
    * [`data/processed`](https://github.com/redhat-et/customer-growth-model/tree/master/data/processed) - directory contains the model predictions and classification output files
    
* [`notebooks`](https://github.com/redhat-et/customer-growth-model/tree/master/notebooks) - Jupyter notebooks developed for exploratory analysis, model training and model classification.