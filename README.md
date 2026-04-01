# 📊 Global Retail Sales Dashboard (Power BI)

## 🚀 Transforming Raw Retail Data into Actionable Insights

---

## 📖 Project Overview  
This project analyzes global retail sales data to uncover insights related to **sales performance, profitability, returns, and regional trends**.

The goal is to build an **interactive Power BI dashboard** that enables business leaders to make **data-driven decisions** by identifying key patterns and problem areas.

---

## 🎯 Business Problem  
The company faced several challenges:
- Inconsistent profitability across regions  
- High discounts reducing overall profit  
- Product returns impacting revenue  
- Uneven sales performance across regions  

---

## 🎯 Objectives  
- Analyze **sales, profit, and quantity metrics**  
- Evaluate **regional and segment performance**  
- Identify impact of **discounts on profitability**  
- Measure and reduce **return rates**  
- Provide actionable insights for decision-making  

---

## 🛠️ Tech Stack  
- **Power BI** – Data Visualization  
- **DAX** – Calculations & Measures  
- **Power Query** – Data Cleaning & Transformation  
- **CSV/Excel** – Data Source  

---

## 📂 Dataset Details  

### Orders Data (Fact Table)  
Contains transaction-level data:
- Order ID, Order Date, Ship Date  
- Customer, Segment, Region, Market  
- Product Details  
- Sales, Quantity, Discount, Profit, Shipping Cost  

### Returns Data (Dimension Table)  
- Order ID  
- Returned (Yes/No)  

### People Data (Dimension Table)  
- Regional Sales Managers  
- Region  

---

## ⚙️ Data Cleaning & Transformation  
- Standardized date formats  
- Converted Sales and Profit into numeric format  
- Handled missing values  
- Removed duplicate records  
- Created calculated column:
  - **Profit Margin = Profit / Sales**  
- Transformed Returns data into a usable flag  

---

## 🧩 Data Modeling  
- Implemented **Star Schema**  
- Fact Table: Orders  
- Dimension Tables: Returns, People  
- Relationships:
  - Orders ↔ Returns (Order ID)  
  - Orders ↔ People (Region)  

---

## 📊 Key DAX Measures  
- Total Sales  
- Total Profit  
- Total Quantity  
- Profit Margin %  
- Return Rate %  
- Year-over-Year Growth %  
- Top 10 Products by Sales  
- Average Shipping Cost  
- Monthly Sales Trend  

---

## 📈 Dashboard Features  

### 🔹 KPI Cards  
- Total Sales  
- Total Profit  
- Profit Margin %  
- Return Rate %  
- YoY Growth  

### 🔹 Visualizations  
- Sales Trend (Monthly & Yearly)  
- Regional Performance  
- Segment-wise Contribution  
- Top 10 Products  
- Sales vs Target  

### 🔹 Interactivity  
- Filters: Year, Region, Segment, Category  
- Drill-through: Region → Product → Customer  
- Conditional Formatting for negative profit  

---

## 📊 Key Insights  
- High discounts in some regions reduced profit margins  
- Certain regions had high sales but low profitability  
- Product returns negatively impacted revenue  
- Technology category contributed significantly to profit  
- Shipping costs affected overall margins  

---

## 💡 Recommendations  
- Optimize discount strategies  
- Reduce return rates through quality improvements  
- Focus on high-performing regions  
- Target high-value customers  
- Optimize shipping costs  

---

## 🚀 How to Use  
1. Download the `.pbix` file  
2. Open in **Power BI Desktop**  
3. Use filters and slicers to explore insights 
