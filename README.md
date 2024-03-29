# Daniel's Project Portfolio
[Github Landing Page](https://github.com/uthrower) | 
[LinkedIn](http://www.linkedin.com/in/danielklchan) | 
<danielkl.chan@mensa.org.hk>
  
# [Algorithmic Trading Bot / Expert Advisors:](https://github.com/urinethrower/Project-Deities)
* Developed 3 trading strategies navigating various markets including forex, stock indices, precious metals and Bitcoin (CFDs)
* Backtested over 1000 single-criteria trading systems, and customised over 20 algorithms from existing indicators
* Strategies include trend-following, confluence trading, scalping
* Risk management system is implemented virtually to avoid stoploss hunting or other broker manipulations
* Advanced features including: hedging, equity curve trading, trade filters, dashboard, etc.
* Created a dynamically linked library `.dll` to handle loop-intensive functions on C++ (e.g. real-time optimisations) and return values to main bot
* Follow my live signal [HERE](https://www.mql5.com/en/signals/2100278)
  
<img src="https://raw.githubusercontent.com/urinethrower/Project-Deities/main/img/Demeter_snapshot.JPG" alt="https://raw.githubusercontent.com/urinethrower/Project-Deities/main/img/Demeter_snapshot.JPG" width="668" height="417">  
  
# [Random forest model on Titanics dataset: R modelled, C++ executed](https://github.com/urinethrower/Project-Titanics)
* A feasibility study towards leveraging machine learning models in quantitative trading in the future
* Random forest model was chosen mainly because of its generally lower risk of over-fitting for small datasets, and it is great for performing feature-based analysis
* Classic Titanics dataset is used for simplicity, 89% accuracy was recorded after minimal tuning hyper parameters
* Model is first built in R, output to flat file, embedded to C++, compiled as `.dll` and imported into MQL4
* Applying multi-threading to further speed up the execution on C++
<div>  
<img src="https://user-images.githubusercontent.com/106392189/171841472-1ef4d16e-7a55-4171-a61a-f2797e2e7fa0.png" alt="https://user-images.githubusercontent.com/106392189/171841472-1ef4d16e-7a55-4171-a61a-f2797e2e7fa0.png" width="410" height="397">
<img src="https://user-images.githubusercontent.com/106392189/171841501-3398e479-3406-4085-a0d0-7fc7933f2a8e.png" alt="https://user-images.githubusercontent.com/106392189/171841501-3398e479-3406-4085-a0d0-7fc7933f2a8e.png" width="367" height="397">
</div>
  
# [Gold Regression Models](https://github.com/urinethrower/gold_regression)
* Linear regression model, and multivariate regression model built on Python for gold price valuation
* Data collected from FRED and EIA by calling API and parsing JSON objects
* Data processed using pandas, modelled using scikit-learn and visualised with seaborn
* Selection of model predictors were based on both fundamental and technical backgrounds
* 15 years worth of gold price was modelled with a R<sup>2</sup> value of 0.87
  
<div>
<img src="https://user-images.githubusercontent.com/106392189/172914317-112b4cbe-3886-4eb2-aef5-bc9517590a02.png">
<img src="https://user-images.githubusercontent.com/106392189/172914325-e4a0a4a1-10a9-4e12-85bd-3b1b5bca2b58.png">
</div>
