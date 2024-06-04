# Stock-price-prediction-of-CNN-model-and-LSTM-model-and-CNN-LSTM-model

A stock price prediction of CNN model, LSTM model and CNN-LSTM model will be performed on various companies: JPMorgan Chase, Tencent Holding Limited and NextEra Energy Inc. 10 years duration from 2013 to 2023 dataset will be extracted from yahoo finance. 

There are missing dates in the dataset. Therefore, the missing dates has been filled in together with the missing data using linear interpolation and backfilling methods. For univariate time series forecasting, 10 days of past data has been used to predict the next closing price. For multivariate time series forecasting, 10 days of different past data of indicators have been used to predict the next closing price, such as open, high, low, close, volume, ups and downs, percentage change. 

The dataset has been separated into train, validation and test set. 90% has been used as training set and 10% has been used as testing set. Among the training set, 10% has been used as validation purpose. 

Finally, use RMSE and MAE as evaluation metrics for the model performance.

Result shows that CNN-LSTM is the most superior model among all three models. 
