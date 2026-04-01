This project focuses on analyzing global retail sales data to uncover insights related to sales performance, profitability, returns, and regional trends.

As a Data Analyst at a fictional company GlobalSuper Sales, the objective was to build an interactive Power BI dashboard that helps business leaders make data-driven decisions.

The dashboard provides a complete view of:

Sales and profit trends
Regional performance
Impact of discounts and returns
Customer and product-level insights
🎯 Business Objectives
Identify key drivers of profitability across regions
Analyze the impact of discounts on profit margins
Track and reduce product return rates
Evaluate regional and segment-wise performance
Enable strategic decision-making using data
🛠️ Tech Stack
Power BI (Dashboard & Visualization)
DAX (Measures & Calculations)
Power Query (Data Cleaning & Transformation)
Excel / CSV (Data Source)
📂 Dataset Details

The project uses three datasets:

1. Orders Data (Fact Table)

Contains transaction-level details:

Order ID, Order Date, Ship Date
Customer, Segment, Region, Market
Product Details
Sales, Quantity, Discount, Profit, Shipping Cost
2. Returns Data (Dimension Table)
Order ID
Return Status (Yes/No)
3. People Data (Dimension Table)
Regional Sales Managers mapped to regions
⚙️ Data Cleaning & Transformation
Standardized date formats for consistency
Converted Sales & Profit into numeric format
Handled missing values (e.g., postal codes)
Removed duplicate records
Created calculated columns:
Profit Margin = Profit / Sales
Transformed Returns data into a usable flag
Built a clean and optimized dataset for analysis
🧩 Data Modeling
Implemented a Star Schema:
Orders → Fact Table
Returns & People → Dimension Tables
Established relationships:
Orders ↔ Returns (Order ID)
Orders ↔ People (Region)
Optimized for efficient reporting and performance
📊 Key DAX Measures
Total Sales
Total Profit
Total Quantity
Profit Margin %
Sales by Region & Segment
Return Rate %
Year-over-Year (YoY) Growth %
Top 10 Products by Sales
Average Shipping Cost
Monthly Sales Trend
📈 Dashboard Features
🔹 KPI Cards
Total Sales
Total Profit
Profit Margin %
Return Rate %
YoY Growth
🔹 Visualizations
Sales Trend (Monthly & Yearly)
Regional Performance Analysis
Segment-wise Contribution
Top 10 Products by Sales
Sales vs Target Comparison
🔹 Interactivity
Slicers: Year, Region, Segment, Category
Drill-through: Region → Product → Customer
Conditional Formatting (highlight losses)
📊 Key Insights
Some regions generated high sales but low profit due to heavy discounting
High return rates in specific regions negatively impacted revenue
Technology category contributed significantly to profits
Certain customer segments delivered higher profitability
Increased shipping costs reduced margins in some regions
💡 Business Recommendations
Optimize discount strategies to protect profit margins
Identify and fix causes of high return rates
Focus on high-performing regions and replicate strategies
Target high-value customers for retention
Optimize shipping methods to reduce operational costs
🚀 How to Use
Download the .pbix file from this repository
Open using Power BI Desktop
Use slicers and filters to explore insights
Interact with visuals for deeper analysis
