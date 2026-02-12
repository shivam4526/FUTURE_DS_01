📊 Business Sales Data Analysis Dashboard
📌 Project Overview
This project analyzes business sales data to identify:
📈 Revenue trends over time
🏆 Top-selling products
💰 High-value categories
🌍 Regional (Country-wise) performance
📊 Key business KPIs
The goal is to transform raw transactional data into actionable business insights that support strategic decision-making.

🎯 Business Objectives
This analysis answers key business questions:
How is revenue trending over time?
Which products generate the highest revenue?
Which regions (countries) perform best?
What is the average order value?
Where should the company focus marketing and inventory efforts?

🗂 Dataset Used
Dataset Name: Online Retail Dataset
Source: UCI Machine Learning Repository
Key Columns:
InvoiceNo – Unique order ID
StockCode – Product code
Description – Product name
Quantity – Number of units sold
InvoiceDate – Transaction date
UnitPrice – Price per unit
CustomerID – Unique customer ID
Country – Customer location

🛠 Technologies Used
Python
Pandas (Data manipulation)
Matplotlib (Basic visualization)
Plotly (Interactive dashboard charts)
Jupyter Notebook
🔎 Data Processing Steps
Loaded dataset using Pandas
Handled missing values
Removed negative quantities (returns)
Converted InvoiceDate to datetime format
Created a new column:
Revenue = Quantity × UnitPrice
Extracted Year-Month for trend analysis

📊 Key Analysis Performed
1️⃣ Revenue Trend Analysis
Monthly revenue calculation
Identified growth and seasonal patterns
2️⃣ Top-Selling Products
Ranked products by total revenue
Identified high-performing SKUs
3️⃣ High-Value Regions
Country-wise revenue aggregation
Identified strongest performing markets
4️⃣ KPI Metrics
Total Revenue
Total Orders
Average Order Value (AOV)

📈 Key Insights
The highest revenue-generating country contributes significantly to total sales.
A small group of top products drives a large portion of total revenue.
Revenue shows seasonal spikes indicating demand cycles.
Average Order Value provides insights into customer purchasing behavior.

💡 Business Recommendations
Increase marketing investment in top-performing countries.
Maintain higher inventory levels for top-selling products.
Run promotions during historically low-performing months.
Introduce bundle offers in high-revenue product segments.
Focus customer retention strategies on high AOV customers.

🚀 How to Run the Project
1️⃣ Install Required Libraries
pip install pandas matplotlib plotly
2️⃣ Place Dataset File
Make sure online_retail.csv is in the project folder.
3️⃣ Run the Script
python sales_analysis.py
Or open Jupyter Notebook and run all cells.
📁 Project Structure
├── online_retail.csv
├── sales_analysis.py
├── README.md

📌 Future Improvements
Add Customer RFM Analysis
Build Sales Forecasting Model (ARIMA/Prophet)
Deploy Interactive Dashboard using Streamlit
Add Customer Segmentation (K-Means)
Add Predictive Analytics using Machine Learning

👨‍💻 Author
Shivam Kumar
Data Analyst | AI & ML Enthusiast
📜 License
This project is for educational and portfolio purposes.
