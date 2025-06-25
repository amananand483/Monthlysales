readme_text = """
# Sales Forecast Project

This project contains a time series forecast of sales data using Holt-Winters Exponential Smoothing.

## Files included:
- `sales_forecast.csv`: Forecasted sales for the next 12 months.
- `sales_with_forecast.csv`: Original historical sales combined with forecast data.
- `sales_forecast_plot.png`: Visualization of historical sales and forecast.

## Summary
The model uses seasonal Holt-Winters method assuming additive seasonality with a seasonal period of 12 months. It forecasts the sales for the upcoming 12 months based on historical trends and seasonal patterns.

## Usage
You can open the CSV files in Excel or any data analysis software. The plot image provides a quick visual understanding of sales trends.

## Author
Aman Anand
"""

with open('README.md', 'w') as f:
    f.write(readme_text)
