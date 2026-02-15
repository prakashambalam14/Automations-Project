🚀 Built an End-to-End Grocery Sales Automation System

As part of improving my data automation skills, I built a complete retail reporting pipeline that simulates real-world daily sales operations.

Since I don’t receive real shop data, I created my own automated data generation system.

🔹 Step 1: Automated Data Generation

Python script generates daily grocery sales CSV

25+ products with realistic transactions

Categories, quantities, revenue & payment methods

🔹 Step 2: Data Cleaning & Validation

Datetime conversion

Numeric validation

Null handling

Duplicate removal

Data quality checks

🔹 Step 3: KPI Calculation
Calculated key retail KPIs:

Total Revenue

Total Transactions

Total Quantity Sold

Average Bill Value

Average Selling Price

Top Payment Method

Peak Sales Hour

Top Selling Product

Category Performance

🔹 Step 4: Automated Reporting

Generates date-stamped Excel report

Multi-sheet structured output (KPIs, Top Products, Category, Raw Data)

🔹 Step 5: Auto Email System

Sends daily KPI summary to shop owner/manager

Excel report attached automatically

📌 This simulates a real-world retail BI automation system where management receives daily performance updates without manual effort.

💻 Tech Stack: Python | Pandas | OpenPyXL | SMTP | Automation Logic

📂 I’ve uploaded the complete project source code to my GitHub repository.
Feel free to explore and share your feedback.

Next step: Integrating with Power BI for live dashboard automation.

Always learning. Always building. 🚀

#DataAnalytics #Python #Automation #BusinessIntelligence #RetailAnalytics #GitHubProjects #DataProjects #PowerBI

If you want, I can also:

Make a shorter high-engagement version

Add a GitHub link call-to-action line that increases clicks

Optimize hashtags for better reach

Or rewrite it in a storytelling format for higher engagement

Tell me what style you want 👌

also create a readme for github repo

Perfect 🔥 this is where your project becomes professional.

Below is a clean, structured, portfolio-ready README.md you can directly copy into your GitHub repo.

🛒 End-to-End Grocery Sales Automation System

An automated retail reporting pipeline that simulates real-world daily grocery sales operations.

This project demonstrates how raw sales data can be generated, cleaned, transformed into KPIs, converted into a structured report, and automatically emailed to management — without manual intervention.

🚀 Project Overview

In real businesses, shop owners and managers receive daily performance reports.

Since I do not receive real sales data from an actual store, I built a complete simulation system that:

Generates realistic grocery sales data daily

Cleans and validates the data

Calculates important retail KPIs

Creates a structured Excel report

Automatically sends the report via email

This project simulates a real Business Intelligence automation workflow.

⚙️ Automation Workflow
1️⃣ Data Generation (generator.py)

Generates daily grocery sales CSV

25+ grocery products

Random realistic transactions (300–600 rows/day)

Includes:

Timestamp

Product Name

Category

Unit Price

Quantity Sold

Total Amount

Payment Method

Output:

input_files/grocery_sales_YYYY_MM_DD.csv

2️⃣ Data Processing & KPI Calculation (report_main.py)

Performs:

✔ Data cleaning
✔ Datetime conversion
✔ Numeric validation
✔ Null handling
✔ Duplicate removal
✔ Data quality checks

📊 KPIs Calculated

The system calculates key retail business metrics:

Total Revenue

Total Transactions

Total Quantity Sold

Average Bill Value

Average Selling Price

Top Payment Method

Peak Sales Hour

Top Selling Product

Category-wise Revenue & Quantity

📁 Report Generation

Creates a structured Excel report:

reports/Daily_Grocery_Report_YYYY_MM_DD.xlsx


Sheets Included:

Summary KPIs

Top Products

Category Performance

Payment Performance

Raw Data

📧 Automated Email System

Sends daily KPI summary in email body

Attaches full Excel report

Simulates real-world reporting to shop owner/manager

🛠 Tech Stack

Python

Pandas

NumPy

OpenPyXL

SMTP (Email Automation)

OS & Datetime modules

📌 How to Run the Project
Step 1: Generate Daily Sales Data
python generator.py

Step 2: Run Report & Email Automation
python report_main.py

🔮 Future Improvements

Integration with Power BI Dashboard

Scheduled automation using Task Scheduler

Profit Margin calculation

Multi-store branch simulation

Customer segmentation

Database integration (SQL)

🎯 Project Purpose

This project demonstrates:

End-to-end data pipeline creation

Retail KPI understanding

Business reporting logic

Automation mindset

Practical BI simulation

👨‍💻 Author

Prakash Ambalam
Aspiring Data Analyst | Automation Enthusiast

Always learning. Always building. 🚀
