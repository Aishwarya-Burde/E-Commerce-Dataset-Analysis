# E-Commerce-Dataset-Analysis
Prepared detailed analysis and visualization in Excel

🛍️ eCommerce Dataset Analysis (Excel Dashboard Project)

This project analyzes an eCommerce sales dataset using Excel for data preparation, DAX formulas for metrics, and an interactive Excel dashboard to visualize trends across platforms like Amazon, Myntra, Flipkart, Meesho, and more.

📁 Dataset Overview

The dataset contains order-wise transaction details from multiple eCommerce channels with customer demographics and shipping information.

📊 Key Columns:

Order ID, Cust ID, Gender, Age, Date, Status

Channel (Amazon, Flipkart, Ajio, Meesho, Myntra, Others)

SKU, Category, Size, Qty, Currency, Amount

Shipping Info: ship-city, ship-state, ship-postal-code, ship-country

B2B Order Flag

🧹 Data Preparation in Excel

Removed duplicates based on Order ID

Cleaned inconsistent Gender entries (e.g., W → Women)

Handled missing/incorrect values (e.g., blank cities, invalid qty)

Standardized Amount format to numeric

Separated and grouped data by City, State, Channel, and Category

Created new calculated columns for KPIs like Age Groups, Region, and B2B vs B2C

🧮 Key DAX Measures Used (Excel Formulas)

Although DAX is native to Power BI, we used Excel-equivalent formulas to calculate the following KPIs:

KPI	Excel Formula / Logic Used

Total Orders
Total Revenue	
Average Order Value	
Gender-wise Order Count
Orders by Channel	
Most Frequent Cities	
B2B vs B2C Analysis

📊 Excel Dashboard

The interactive Excel dashboard provides comprehensive insights with the following visuals:

📦 Total Orders, 💰 Total Revenue, 👤 Unique Customers

🌍 Orders by Channel (Amazon, Myntra, Flipkart, etc.)

👕 Category-wise Sales (Kurta, Set, Western Dress, etc.)

📍 Top Cities and States

🚻 Gender-wise Distribution

📈 Revenue Trend (Date-wise)

📸 Dashboard Preview

📌 A clean Excel dashboard built for performance and clarity

📌 Key Insights

Top Channels: Myntra and Amazon generated the highest number of orders.

Popular Categories: "Kurta" and "Set" products were most purchased.

Gender Distribution: Women account for 80%+ of the total orders.

City Highlights: Gurugram and Bengaluru were top shipping destinations.

All Orders Are B2C: No business orders (B2B) found in this dataset.

Age Demographics: Most shoppers were aged between 40–60 years.

▶️ How to Run This Project

Clone or download this repository.

Open eCommerce_Dashboard.xlsx in Excel 2016+.

Interact with slicers and filters (channel, city, category).

Review KPIs and visual insights directly on the dashboard sheet.

📬 Contact

Aishwarya Burde
aishwaryaburde2000@gmail.com
LinkedIn: www.linkedin.com/in/aishwarya-burde

