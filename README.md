# COVID-19 Predictions: India

_All source codes are python notebooks. The path to csv files will have to be changed while running the notebook_.

* cleaning_eda_india.ipynb - Data cleaning and Feature Engineering for India data

* cleaning_eda_worldwide.ipynb - Data cleaning and Feature Engineering for Worldwide data

* Linreg+ARIMA.ipynb - Runs linear regression model and arima model on cleaned data and plots the results of both. The regression model is further used to predict daily cases for the next 20 days.

* ARIMA_Prophet.ipynb: contains basic exploration of data and univariate/multivariate predictions using statistical models like Arima and Prophet.

* hmmV2.ipynb - runs a multivariate HMM model to predict new cases in India, displays predictions for various hyperparameters

* LSTM_India.ipynb - Using India’s data, runs univariate and multivariate LSTM models to predict the number of new cases.

* LSTM_worldwide.ipynb - Using Worldwide data, runs univariate and multivariate LSTM models to predict the number of new cases in India

* Seq2Seq.ipynb - Using the confirmed cases of India runs univariate Seq2Seq models to predict the number of new cases in the second wave

* Lockdown_Impact.ipynb - Uses linear regression model to predict impact of lockdown on 2nd wave

#### Details of the various runs on the deep learning models can be found at https://wandb.ai/covid19india/projects
