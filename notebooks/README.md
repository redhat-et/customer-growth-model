# Growth Model Notebooks

The directory contains the notebooks used for developing growth model. The following list describing each of them. 

- [growth_model_eda.ipynb](growth_model_eda.ipynb) - pre-processes the public dataset from [Kaggle](https://www.kaggle.com/datasets/census/business-and-industry-reports?select=notes.txt) to be used for training an Auto ARIMA time series forecasting model
- [growth_model_forecast.ipynb](growth_model_forecast.ipynb) - develops a time series forecasting model on the pre-processed dataset to forecast future revenues
- [growth_model_classification.ipynb](growth_model_classification.ipynb) - classifies customers based on their potential to grow by using the forecasted data
- [helper_functions.ipynb](helper_functions.ipynb) - provides a set of helper functions that are used in other notebooks to perform various tasks

To run these notebooks, make sure to install the required package dependencies from the [Pipfile](../Pipfile) file and have a running instance of Jupyter Notebook.
