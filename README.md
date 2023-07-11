# Time-Series-Analysis
Austin-City-Crime-Forecast
![image](https://github.com/anidurg/Time-Series-Analysis/assets/102254578/c05c1eb5-b56f-459f-b8e6-a01fe7265c78)
![image](https://github.com/anidurg/Time-Series-Analysis/assets/102254578/464f9841-297c-4f95-9ce0-63e4ab7c2b70)

AUTO-ARIMA and Prophet was done with twenty time series (ten Austin Police Department Sectors and two major crimes with code of 600 and 601
code 600 is for Thefts and code 601 for Burglary
Ten sectors are George, Henry, Baker, David, Charlie,Adam, APT, Edward,Frank, IDA, APT
Year of crimes were chosen from 2022 and above
Downsampling was done to make it a weekly time series
Implemented Pivot method so each time series is a separate column
I am using two methods for modeling this multiple time series, viz.,Auto_Arima method and Prophet method
I split the data where cut off date for train set is 2022-12-30
Forecast for both the methods were evaluated based on MAPE values.
I had applied only one time series with XGBoost algorithm. Given more time, I would apply for all the time series and evaluate its performance.
There is a lot of scope to imporve this project. Given more time, I would have tried to test with more powerful regression algoriths like RandomForestRegressor, LightGBM ensemble algorithm.
