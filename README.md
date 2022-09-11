# ML_Power_consumption_EDA_and_forecasting
## GOAL 
The goal of this notebook to perform the Timeseries forecasting and predictive analysis on `Global_active_power` variable, which represents the total power consumption.

## Description
The data is taken from kaggle and can be downloaded from [here](https://www.kaggle.com/uciml/electric-power-consumption-data-set/data). 
The data include measurements of electric power usage in one household taken at a one-minute sample rate during a nearly four-year period. This is a regression problem. `Global_active_power` variable is the only feature that we are interested in. 
Timeseries forecasting of the `Global_active_power` variable can be performed by reformulating the problem into a supervised learning problem.

## Notebook

Jupyter notebook `Power_consumption_EDA_and_forecasting.ipynb` contains: <br>
- EDA
- Statistical test to check normality of the data
- Statistical test to check whether timeseries is stationary.
- Timeseries forecasting 

## ML Models
| Method  | Number |
| ------------- | ------------- |
| RNN (LSTM,GRU)  | 2 layer  |
| Dropout value|  0.5 |
| Optimizer  | adam  |
| Batch size  | 64 |
| Nodes   |  128   |
|Learning Rate| 0.001 |
| RMSE  |2.37(LSTM), 2.34(GRU) |

## Results

Timeseries forecasting of `Global_active_power`: 

<img src="https://github.com/immayankprakash/ML_Power_consumption_EDA_and_forecasting/blob/master/images/Forecast.png" >
