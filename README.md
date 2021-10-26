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
MODEL | Linear Regression | Random Forest Regressor | XGBoost Regression |
--- | --- | --- | --- |
R2 SCORE | 0.069 | 0.767 | 0.600 |
RMSE | 8471841.272527765 | 4233978.736183579 | 4463225.761568096 |
MSE | 71772094546904.88 | 17926575938454.695 | 19920384198725.105 |
MAE | 1559419.4148334502 | 830613.5209224033 | 941689.3147012601 |

