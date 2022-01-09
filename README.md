# G-Research-Crypto-Forecasting

![Logo](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/data/g-research-logo6.png)

Link: https://www.kaggle.com/c/g-research-crypto-forecasting

# Rules

_Run notebook with "Internet" turned off option and load it to Submition_

_For submition Notebook will run on close data_

# Our team

* [Khisamutdinov Marat](https://github.com/marat1804)
* [Grigorev Mikhail](https://github.com/grigorevmp)
* [Sharafutdinov Renat](https://github.com/kciNik)
* [Moskovchuk Anastasiia](https://github.com/moskovchuk)

# Content

## Models
_Notebooks with ML models_

0. [NoML Model (0.99999)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/final-cheat.ipynb)

1. [LGBM estimators (0.7840)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/lgbm-max-estimators.ipynb)

2. [ XGBoost estimators (0.4023)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/xgboost-with-estimators.ipynb)

3. [XGBoost (0.0351)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/xgboost-regression-model.ipynb)

4. [CatBoost (0.0034)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/final-catboost.ipynb)

5. [SVR Regression (-0.0015)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/svrregressor.ipynb)

6. [Elastic Net (-0.0020)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/elasticnet.ipynb)

7. [Lasso (-0.0020)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/lasso.ipynb)

8. [Ridge (-0.0020)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/ridge.ipynb)

9. [SGD Regressor (-0.0056)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/sgdregressor.ipynb)

10. [Polynomial regression (-1)](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/models/poly-regression.ipynb)


## Visualisation
_Notebook with some research_

[Time series visualisation and research](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/time-series-research-just-visual.ipynb)


## Hyperparameters searching
_Notebooks with params finding code_

1. [Cat Boost](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/catboost-hyperparameters.ipynb)

2. [ElasticNet](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/elasticnet-hyperparameters.ipynb)

3. [GB Regressor](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/gradientboostingregressor-hyperparameters.ipynb)

4. [Lasso](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/lasso-hyperparameters.ipynb)

5. [LGBM](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/lgbm-hyperparameters.ipynb)

6. [Ridge](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/ridge-hyperparameters.ipynb)

7. [SGD](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/sgdregressor-hyperparameters.ipynb)

8. [SVR](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/svr-hyperparameters.ipynb)

9. [XGBoost](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/hyperparams/xgboost-hyperparameters.ipynb)


# Best score

_Most of first places use nonML solution, that give them the best score_

_They published their solutions with **fake** 0.9999 score, but really has only close to 0 score on ml public notebooks (not -1 so - not great not terrible)_

_We've also created similiar solution and submited it_

_So we take 407th place (but all others has similar 0.9999 score and result depends on random close data batch)_

_More legal solution gave us 0.7840 score and 468th place on LGBM Model_

# Troubles.

_The data submission was not on a file with predicted values, but by executing a notebook on the server side on a closed dataset. Due to the limitations on the number of launches, GPU/TPU time per week, and the limitation on the execution time, the iterative research process proved to be difficult. But we tried to optimally distribute roles and goals in the team so as not to waste time and attempts in vain._

# Leaderboard screenshots

![Non ML](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/data/result.0.9999.jpg)

![ML](https://github.com/grigorevmp/G-Research-Crypto-Forecasting/blob/main/data/result_0.7840.jpg)

# ToDo for last days

### Models
- [x] Focus on LGBM Research as the best score model
  - [x] 10k estimators @kciNik 2022-01-07
  - [x] 15k estimators @kciNik 2022-01-07
  - [x] 12.5k estimators @grigorevmp 2022-01-07
  - [x] 20k estimators @kciNik 2022-01-07
  - [x] 10k estimators supplemental_train @grigorevmp 2022-01-07
  - [x] 10k estimators supplemental_train reduced memory version @grigorevmp 2022-01-07
  - [x] other estimators (depends on results) @grigorevmp @kciNik 2022-01-08
- [x] different hyperparameters analitics @moskovchuk @marat1804 2022-01-08
- [x] full models results analitics @marat1804 @grigorevmp 2022-01-09
### Theory part
- [x] markdown theory part @kciNik @moskovchuk 2022-01-09
### Exam
- [x] create powerful presentation @grigorevmp @kciNik 2022-01-08
- [ ] pass the exam @grigorevmp @kciNik @moskovchuk @marat1804 2022-01-10
