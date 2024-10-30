# Forecasting-energy-consumption
In this project, the goal is to accurately forecast energy conumption. That means I need to find and choose the best suitable model that is accurate and fast to train. \
Since the data represents a single linear time-series with a clear repetitive pattern, I first try to fulfill the job with simple statistical methods like AR, MA, ARIMA, SARIMAX, and then experiment with more advanced models to see if they can outperform the baseline. Specifically, I try XGBoost, as it can be powerful with non-changing (stationary) time-series like this.
