# Enterprise Analytics & Decision Support Using Excel
In this project, I was assigned to work as a consultant for a company. My main task was to transform raw transactional data into decision-ready insights using Excel.
## Tab 1: Data Engineering & Derived Metrics
In this tab, I converted the raw data into an Excel table, confirming that the data in all columns is of the correct data type.

Then, I created a "Calculated Metrix" section, calculating:
- *Profit margin* = Profit/Sales
- *Shipping delay* = Ship Date − Order Date
- *High discount flag*: Flag orders where Discount > 20%
- *Loss-Making Transaction Flag*: Flag orders where Profit < 0
## Tab 2: Multi-Dimensional Performance Analysis
I used PivotTables to answer following questions:

**1. Regional Strategy**
- Which region generates the highest revenue?
- Which region generates the highest profit?
- Is high revenue correlated with high profitability?

**2. Discount Impact Analysis**
- Does higher discount lead to lower profit margin?
- Identify discount threshold where average profit becomes negative.

**3. Segment & Category Performance**
- Which segment (Consumer, Corporate, Home Office) is most profitable?
- Which product category has the lowest margin?
- Which sub-category is consistently loss-making?

**4. Operational Efficiency**
- Compare average shipping delay by:
  + Region
  + Ship Mode
- Does faster shipping correlate with higher profitability?
## Tab 3: Forecasting & Predictive Insights
I created a PivotTable and PivotChart to aggregate monthly total sales and observe monthly profit trend.

Then, I used **FORECAST** function to forecast the next 12 months of Sales and Profit to answer these questions:
1. Is revenue trending upward or downward?
2. Is profit growth sustainable?
3. What risk factors are visible?
## Tab 4: What-If & Scenario Analysis
In this tab, I used **Data Tables** to see that what will happen to Revenue, Profit, and Profit Margin if there is an increase in discount by 10%
## Tab 5: Executive Dashboard
I created a professional executive dashboard containing:
1. KPI cards:
- Total Revenue
- Total Profit
- Average Profit Margin
- Average Shipping Delay
- % Loss-Making Orders
2. Interactive Features
## Tab 6: Summary Report
## Tab 7: Strategic IT Analysis
## Tab 8: Strategic Recommendation
Based on the performance of each branch, I used **(1) Linear Regression** and **(2) KPI Weights** to determine who should be promoted as the next Regional Director.
