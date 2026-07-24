# RetailIQ_End_to_End_Sales_Analytics_Platform
RetailIQ: End-to-End Sales Analytics Platform is a business intelligence project that analyzes retail sales data using Python, SQL, Excel, and Power BI. The project includes data cleaning, EDA, SQL-based business analysis, KPI calculation, and an interactive Power BI dashboard to visualize sales trends, customer insights, product performance.
Dashboard 1 – Executive Overview
KPI Cards
💰 Total Sales
📈 Total Profit
🛒 Total Orders
👥 Total Customers
📦 Total Quantity Sold
💵 Average Order Value
📊 Profit Margin %
Charts
Monthly Sales Trend (Line Chart)
Monthly Profit Trend (Line Chart)
Sales by Category (Clustered Bar Chart)
Sales by Segment (Donut Chart)
Sales by Region (Map)
Slicers
Year
Month
Category
State
Dashboard 2 – Customer Analytics
KPI Cards
Total Customers
Repeat Customers
Average Customer Spend
Charts
Top 10 Customers (Bar Chart)
Sales by Customer Segment (Pie Chart)
Customer-wise Revenue (Column Chart)
Customer Distribution by State (Map)
Dashboard 3 – Product Analytics
KPI Cards
Total Products
Best Selling Product
Highest Profit Product
Charts
Top 10 Products by Sales
Bottom 10 Products
Sales by Category
Profit by Category
Quantity Sold by Product
Dashboard 4 – Regional Performance
KPI Cards
Best State
Lowest Sales State
Highest Profit State
Charts
Sales by State (Filled Map)
Profit by State (Bar Chart)
Sales by City
Shipping Cost by State
Regional Sales Comparison
DAX Measures
Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Orders = DISTINCTCOUNT(Sales[OrderID])

Total Customers = DISTINCTCOUNT(Sales[Customer])

Total Quantity = SUM(Sales[Quantity])

Average Order Value =
DIVIDE([Total Sales],[Total Orders])

Profit Margin % =
DIVIDE([Total Profit],[Total Sales])*100
Dashboard Theme
Primary Color: Dark Blue (#1F4E79)
Accent Color: Orange (#F28E2B)
Background: White
Font: Segoe UI
Rounded Cards with subtle shadows
Interactive slicers at the top of every page
Dashboard Layout
---------------------------------------------------------
| Logo | RetailIQ Sales Analytics Dashboard              |
---------------------------------------------------------
| Total Sales | Profit | Orders | Customers | Margin %   |
---------------------------------------------------------
| Monthly Sales Trend           | Sales by Category       |
---------------------------------------------------------
| Sales by State                | Segment Distribution    |
---------------------------------------------------------
| Year | Month | Category | State (Slicers)              |
---------------------------------------------------------
