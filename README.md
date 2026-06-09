#  Zepto Hyperlocal Demand Predictor

A time-series machine learning pipeline designed to forecast hourly consumer demand velocity for quick-commerce platforms using historical lags and environmental features.

##  Features
* **Hourly Granularity:** Focuses on micro-fulfillment center (dark store) timelines rather than standard daily metrics.
* **Environmental Shocks:** Simulates probability-driven event surges (e.g., flash rainstorms, live IPL cricket matches) that trigger non-linear demand jumps.
* **Feature Engineering:** Implements 1-hour and 24-hour historical lags along with 3-hour moving averages without data leakage.
* **Performance Visualization:** Includes evaluation scripts to plot model forecasts against actual volatile demand curves.

##  Model Performance
* **Mean Absolute Error (MAE):** 1.52 units/hour
* **Root Mean Squared Error (RMSE):** 4.96 units/hour
