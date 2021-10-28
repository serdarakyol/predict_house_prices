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

MODEL | LinearRegression | Lasso | RandomForestRegressor | XGBRegressor |
--- | --- | --- | --- | --- |
R2 SCORE | 0.999 | 0.999 | 0.993 | 0.916 |
RMSE | 3405.400 | 7215.780 | 602419.448 | 2169861.151 |
MSE | 11596752.752 | 52067489.628 | 362909192486.382 | 4708297416383.404 |
MAE | 2943.557 | 4952.487 | 13044.796 | 78831.935
