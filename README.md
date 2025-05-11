📊 Amazon Sales Analysis Dashboard – Power BI
This Power BI project presents an interactive and insightful Sales Analysis Dashboard built using Amazon product sales data. It demonstrates how raw data can be transformed into actionable insights through compelling visual analytics.

🔍 Project Overview
This dashboard helps stakeholders gain insights into:

📆 Year-to-Date (YTD) Sales

📆 Quarter-to-Date (QTD) Sales

📦 Total Products Sold

📝 Total Customer Reviews

🏆 Top Performing Product Categories

📊 Sales Trends (Monthly & Weekly)

🏅 Top 5 Products by Sales & Reviews

💡 Key Features
📈 Dynamic KPI Indicators

📅 Sales Trend Visualizations by Month & Week

🛍️ Sales by Product Category

🌟 Top Products by Revenue and Reviews

🔁 Interactive Filters for Product & Quarter Selection

🧠 Optimized Data Model with One-to-Many Relationship (Fact-Dimension)

🧱 Data Model
Fact Table: Amazon Sales Data (Order Date, Price, Reviews, Product Info)

Dimension Table: Custom Date Table with Month, Quarter, and Calendar logic

Relationship: One-to-Many (Date Table[Date] → Amazon_Data[Order Date])

🛠️ Tools Used
Microsoft Power BI

DAX (Data Analysis Expressions)

Data Modeling using Star Schema

Custom Date Table Logic

📷 Dashboard Snapshots
Replace below image links with GitHub-uploaded images after pushing files.
![Screenshot 2025-05-11 142402](https://github.com/user-attachments/assets/919cab7e-0c1f-4dc1-b809-66e218e0f71d)
![Screenshot 2025-05-11 143705](https://github.com/user-attachments/assets/4b1b78b9-c858-4b53-8d79-23dba505cf8c)


📁 Project Structure
bash
Copy
Edit
amazon-sales-powerbi-dashboard/
│
├── 📊 Amazon_Sales_Analysis.pbix         # Power BI File
├── 📁 assets/                            # Dashboard screenshots
├── 📄 README.md
└── 📄 .gitignore
⭐ How to Use
Clone the repository

Open the .pbix file using Power BI Desktop

Explore the dashboard with filters and slicers

