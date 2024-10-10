# Project Overview
This project focuses on predicting sales for Rossmann stores using time series forecasting models such as Prophet, ARIMA, and SARIMA. After experimenting with various models and features, Prophet proved to deliver the best results for long-term predictions, especially when factoring in seasonality, holidays, and promotional events. The model forecasts sales for up to four months beyond the latest dataset entries.

The goal of this project was to analyze historical sales data, understand key drivers of fluctuations, and build a robust predictive model that could assist Rossmann in making data-driven decisions to optimize inventory, staffing, and promotional strategies.

### Key Highlights
- **Data Exploration**: Conducted detailed analysis of daily, monthly, and yearly sales, uncovering patterns and seasonal trends.
- **Outlier Detection**: Identified key outliers around holidays, suggesting that seasonal peaks are driven by external factors, not just promotions.
- **Modeling Approach**- : Tested multiple models (ARIMA, SARIMA, Prophet), with Prophet outperforming others in handling complex seasonality and holiday effects.
- **Forecasting**: Successfully predicted four months of sales, providing valuable insights for future business planning.
# Project Approach
- **Data Preparation**-: Cleaned and processed sales data, creating new time-based features and aggregating metrics for better insights.
- **Modeling**: Implemented Prophet with custom seasonalities, holiday effects, and promotional events as regressors.
- **Evaluation**: Models were evaluated using MSE and MAE, with Prophet achieving the best performance.
- **Final Prediction**: Produced a reliable sales forecast for four months beyond the dataset, helping to anticipate high-demand periods.

# Tools and Libraries
- Prophet for time series forecasting
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn, Plotly for visualization
- Sklearn for model evaluation

# Conclusion
This project showcases my ability to tackle complex time series forecasting challenges, from data exploration to model fine-tuning. The combination of holidays, promotional effects, and seasonality helped create a robust forecasting system that can aid decision-making in retail environments like Rossmann.
