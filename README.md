# Time-Series-Forecasting

This notebok implements a Deep Neural Network based forecasting model, using LSTM. The dataset contains 228 time series each with 12672 timestamps. However, forecasting is done only the first two time series i.e first 2 columns in the dataset. In each of the time series last 1440 timestamps are for test. Similarly second last
1440 time stamps are for validation. Window size i.e number of past values to be used for predicting future values is 12 and horizon i.e number of future values to be
predicted is 9. A dataloader that prepares the data according to the description given is also built. The prediction accuracy is measured using Root Mean Squared Error (RMSE) of the test set for each of the timeseries.

