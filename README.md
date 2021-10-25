# Algorithmic_Trading_Bot

Algorithmic Trading Bot is an algorithmic trading systems driven by machine learning, which allows users to automate trade decisions and manage assets in highly dynamic environments.

# Usage

Algorithmic Trading Bot was developed by using a combination of financial Python programming and machine learning. The system uses an algorithmic trading model that analyzes pricing data & stocks, learns and adapts to new data, and makes decisions about when to buy or sell shares.
Our algorithmic trading system utilized the simple moving average (SMA) logic using a window size of 4 days and name it “sma_fast”, and another SMA column using a window size of 100 days, and name it “sma_slow” to calculate the average price of a stock over a rolling period of a specific number of days.
Backtesting was also performed to gauge the risk/reward characteristics.
 
# Summary Report

Our machine learning model learns from the training dataset and makes predictions based on the testing dataset, which is X_test_scaled in this case. The training_signal_predictions variable contains our predicted values, which will exist in an array of 1 and −1 values. Our classification report shows a precision of 0.43  for the −1 class and 0.56 for the 1 class. The recall is 0.04 for the −1 class and 0.96 for the 1 class which indicates that the model (based on the testing data) is better at predicting the 1 class than the −1 class. Our classification report shows an accuracy of 0.55 or 55%. Our predictions yielded better returns only during 2016 & underperformed for the remaining of the analyzed period. 


# Visualization

![alt text](https://github.com/GGCorrochano/ML_Trading_Bot/blob/main/Strategy_Returns_plot.png?raw=true)
![alt text](https://github.com/GGCorrochano/ML_Trading_Bot/blob/main/Predictions_Cumulative_Return_plot.png?raw=true)
![alt text](https://github.com/GGCorrochano/ML_Trading_Bot/blob/main/Predictions2_Cumulative_Return_plot.png?raw=true)

# Contributing

Pull requests are welcome. Please open an issue to discuss before executing any changes.

Please make sure to update tests as needed.

# License
BSD-2-Clause https://opensource.org/licenses/BSD-2-Clause

