# Sales & Demand Forecasting Dashboard

**Internship:** Future Interns, Machine Learning Track, Task 1

## About
A Power BI dashboard that analyses Superstore sales (2014-2017) and forecasts the next 6 months.

## Dataset
Superstore Sales Dataset (Kaggle): https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## What I did
- Cleaned the data in Power Query (fixed date formats, removed duplicates)
- Built a date table and time-based fields (year, month, quarter)
- Created a monthly sales trend with a 6-month forecast (95% confidence, seasonality 12)
- Built KPI cards, a category chart and a year filter

## Key insights
- Sales peak every November and December, so extra stock should be ordered by October
- Sales dipped in 2015, then grew strongly in 2016 and 2017
- Technology is the top-selling category
- The forecast band is wide, so stock levels should be planned conservatively

## Files
- `Sales_Forecast_Dashboard.pbix` - Power BI file
- `dashboard_overview.png` - dashboard screenshot
- `Sales_Forecast_Dashboard.pdf` - PDF export

## Tools
Power BI Desktop, Power Query, DAX
