# House Price Prediction
This repository goal is analyse and predict house prices in USA

## USAGE
Enter the predict_house_prices and follow the below codes
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```
data_visualize.ipynb file for analyse the dataset
train.ipynb for train different models and see the results

## RESULTS
MODEL | XGBRegressor | RandomForestRegressor | Lasso | LinearRegression |
--- | --- | --- | --- | --- |
R2 SCORE | 0.614 | 0.532 | 0.078 | 0.077 |
RMSE | 4661217.449263945 | 5128552.104690856 | 7203058.581229313 | 7206951.692021304 |
MSE | 21726948109322.676 | 26302046690529.016 | 51884052924621.25 | 51940152691128.734 |
MAE | 936161.1389531724 | 821550.8325420639 | 1460698.8133045027 | 1486661.9948830162 |

