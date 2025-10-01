# Walmart-Sales-Forecast
Analysis and forecasting of Walmart weekly sales using historical data and Excel

**Objective:**
The goal of this project is to analyze historical Walmart sales data and forecast weekly sales for each store and department. This helps in inventory management, marketing decisions, and planning for holiday and non-holiday periods.

**Datasets Used:**
1.Sales Table: Contains store information, type, and size.
Columns: Store, Type, Size
Example: 1, A, 151315

2.Features Table: Contains store-level weekly features including weather, fuel price, markdowns, CPI, unemployment, and holiday indicators.
Columns: Store, Date, Temperature, Fuel_Price, MarkDown1-5, CPI, Unemployment, IsHoliday
Example: 1, 05-02-2010, 42.31, 2.572, NA, NA, NA, NA, NA, 211.096, 8.106, FALSE

3.Train Table: Contains historical weekly sales data for each store and department.
Columns: Store, Dept, Date, Weekly_Sales, IsHoliday
Example: 1, 1, 05-02-2010, 24924.5, FALSE

4.Test Table: Contains the data for which sales need to be forecasted.
Columns: Store, Dept, Date, IsHoliday
Example: 1, 1, 02-11-2012, FALSE

5.Analysis Performed in Excel:
Summary statistics and visualizations of sales trends over time.
Comparison of holiday vs. non-holiday sales.
Sales performance by store and department.
Use of pivot tables, charts, and slicers for interactive dashboards.

**Key Insights:**
Weekly sales fluctuate seasonally, with peaks during holidays.
Certain stores or departments consistently outperform others.
External factors like markdowns, fuel price, and unemployment may impact sales trends.
