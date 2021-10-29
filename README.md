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

MODELs/SCOREs |  R2 SCORE |  RMSE |  MSE |  MAE
--- | --- | --- | --- | --- |
RandomForestRegressor | 0.6512664208122405 | 4748386.263317866 | 22547172105665.81 | 807322.6456264602
XGBRegressor | 0.6239738019806718 | 4930695.784860931 | 24311760922845.35 | 929608.2711104134
Lasso | 0.0764374947095573 | 7727380.594256299 | 59712410848488.82 | 1451490.140819531
LinearRegression | 0.07612022514801176 | 7728707.7660077885 | 59732923732349.09 | 1472770.2875585465
