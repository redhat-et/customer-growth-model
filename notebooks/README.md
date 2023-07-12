# Growth Model Notebooks

This directory contains the Jupyter notebooks used for developing the growth model. Each of them is described as follows: 

- [growth_model_eda.ipynb](growth_model_eda.ipynb) - In this notebook, we pre-process the public raw dataset from [Kaggle](https://www.kaggle.com/datasets/census/business-and-industry-reports?select=notes.txt) to be used for training an Auto ARIMA time series forecasting model
- [growth_model_forecast.ipynb](growth_model_forecast.ipynb) - This notebook develops a time series forecasting model on the pre-processed dataset to forecast future revenues
- [growth_model_classification.ipynb](growth_model_classification.ipynb) - This notebook classifies customers/users based on their potential to grow by using the forecasted data
- [helper_functions.ipynb](helper_functions.ipynb) - This notebook provides a set of helper functions that are used in other notebooks to perform various tasks

To run these notebooks, make sure to install the required package dependencies from the [Pipfile](../Pipfile) file and have a running instance of [Jupyter Notebook](https://jupyter.org/).
