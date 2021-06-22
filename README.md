# Rise of the machines!
![maxresdefault](https://user-images.githubusercontent.com/75221323/122645946-940d0680-d0e2-11eb-8a4c-c5188210c1ff.jpg)


## Project Summary
This project is motivated by the desire to better understand and implement some of the more common machine learning trading algorithms. We will be be experimenting with various supervised and unsupervised learning techniques, and benchmarking the performance of the models against passive ETFs and active mutual funds.

## Contributors:
* Val
* Felix
* Sam

## Libraries and Dependancies
* Alpaca API
* Python
* sklearn
* NumPy
* Pandas

## Steps
1. **Data Generation:** Gather and prepare historical return data for training and testing

2. **Create trading signals**
  * [Simple Moving Average (SMA)](https://www.investopedia.com/terms/m/movingaverage.asp)
  * [Exponential Moving Average (EMA)](https://www.investopedia.com/terms/e/ema.asp)
  * [Relative Strength Index (RSI)](https://www.investopedia.com/terms/r/rsi.asp)
  * [Moving Avereage Convergence Divergence (MACD)](https://www.investopedia.com/terms/m/macd.asp)
  * [Bollinger Bands](https://www.investopedia.com/terms/b/bollingerbands.asp)
  
3. **Train and compare multiple Machine Learning Algorithms:** Compare prediction performance of multiple ML-Algorithms on dimensions of accuracy, performance, and efficiency (Sharpe Ratio). Alogorithms in scope:
  * [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
  * [AdaBoostClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html)
  * [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
  * [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
  * [GradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
  * [XGBClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
