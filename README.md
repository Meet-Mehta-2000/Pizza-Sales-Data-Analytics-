# Pizza-Sales-Data-Analytics-

Pizza Sales Analysis – End-to-End Data Analytics Project

This Pizza Sales Analysis project is a complete data analytics case study focused on deriving key insights from transactional sales data of a pizza store. It combines data cleaning, SQL querying, KPI calculation, visualization, and business interpretation to help management make informed, data-driven decisions.

📁 Project Type: Data Analytics / Business Intelligence   
🧰 Tools Used: SQL | Python | Power BI | Tableau | Excel  
📊 Dataset: pizza_sales.csv  
📄 Document: Business Requirements Document (BRD)  

## 🎯 Project Overview

The project analyzes historical pizza sales data to understand business performance and uncover key insights related to sales trends, product performance, and customer behavior.

It answers important business questions such as:   
Q)What is the total revenue generated?  
Q)Which pizza category and size perform the best?  
Q)Which pizzas are the top 5 and bottom 5 sellers?  
Q)How do sales vary by day, month, and time of day?  
Q)What is the average order value (AOV) and average pizzas per order?  

### 🧠 Business Objectives
-Identify overall revenue, total pizzas sold, and total orders.   
-Determine sales distribution by pizza category, size, and type.  
-Analyze time-based trends in sales (daily, monthly, and hourly).  
-Highlight best- and worst-selling pizzas by revenue and quantity.  
-Understand customer purchasing behavior through KPIs.  
-Build interactive dashboards to visualize performance insights.  

### 🧾 Data Description

Dataset: pizza_sales.csv  

-order_id:Unique identifier for each order  
-pizza_id:	Unique identifier for each pizza  
-pizza_name:Name of the pizza sold  
-quantity:	Number of pizzas sold per order  
-total_price:	Total revenue for that transaction  
-date:	Order date  
-time:	Order time  
-pizza_category:	Pizza classification (Classic, Veggie, Supreme, Chicken)  
-pizza_size:	Size of pizza (S, M, L, XL)  

### 📊 Key Performance Indicators (KPIs)

-Total Revenue:	Σ total_price	Total income generated  
-Total Pizzas Sold:	Σ quantity	Total pizzas sold  
-Total Orders:	COUNT(order_id)	Number of unique orders  
-Average Order Value (AOV):	Total Revenue ÷ Total Orders	Average value per order  
-Average Pizzas per Order:	Total Pizzas Sold ÷ Total Orders	Customer purchase behavior  

### 📈 Analysis & Visualizations
🔹 Daily Trend  
Sales performance by day of the week - Helps optimize staffing and operations planning  

🔹 Hourly Trend  
Sales by hour of the day - Identifies peak sales hours for inventory and staffing  

🔹 Monthly Trend  
Tracks monthly revenue and order - Highlights seasonality and campaign effectiveness 

🔹 % of Sales by Category  
Compares revenue and quantity across pizza categories - Shows customer preference distribution  

🔹 % Sales by Size  
Analyzes revenue contribution by pizza size (S, M, L, XL) - Guides inventory and pricing decisions  

🔹 Top 5 Best-Selling Pizzas  
Highlights the most popular products by revenue and quantity  

🔹 Bottom 5 Least-Selling Pizzas  
Identifies underperforming products for potential menu optimization  

### 📊 Dashboards
🔹 Power BI Dashboard  
Dynamic KPIs and filters - Interactive trend visuals and category breakdowns  

🔹 Tableau Dashboard  
Visually rich storytelling with interactive charts - Time-based and category-based filters  

🔹 Excel Dashboard  
Slicers, pivot charts, and custom visuals - Fully dynamic AOV, sales, and trend tracking  

### 📈 Business Insights
- Classic pizzas generate the highest revenue share.
- Large (L) pizzas contribute most to sales volume.
- Fridays and weekends show peak order frequency.
- Afternoon (12 – 1 PM) and evening (4–9 PM) hours drive maximum sales.
- The Classic Deleuxe pizza and The Barbecue Chicken pizza are top-selling pizzas and should be featured more in marketing campaigns.
- The Brie Carre is lowest-selling pizza and  may need recipe updates, promotions, or removal.

### 🧩 Deliverables

📘 Jupyter Notebook: Python data cleaning and analysis   
🗃️ SQL Queries: Data extraction and KPI generation    
📊 Power BI / Tableau / Excel Dashboards: Interactive visualizations   
🧾 Business Requirements Document (BRD): Detailed project scope and objectives    
📄 Insights Report: Actionable recommendations for management  

### 💡 Recommendations

- Focus marketing on top-performing pizza categories
- Optimize menu pricing and promotions around peak demand hours
- Reassess least-selling pizzas to reduce waste and improve profitability
- Use data dashboards for ongoing performance tracking

👨‍💻 Author  
Meet Mehta
