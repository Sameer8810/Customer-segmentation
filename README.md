📊 Customer Segmentation Analysis (RFM Model)
📌 Overview
This project applies RFM Analysis (Recency, Frequency, Monetary) to segment customers and identify high-value groups.
The goal is to provide actionable insights for marketing strategies and customer retention.
The results are presented both in Python visualizations and an interactive Power BI dashboard.

🎯 Objectives
Calculate RFM metrics for each customer.

Assign RFM scores and categorize into segments (Champions, Loyal Customers, Lost Customers, etc.).

Analyze segment behavior and monetary contribution.

Create an interactive dashboard for business stakeholders.

📂 Dataset
Source: Online Retail dataset (UCI Machine Learning Repository / Kaggle)

Description: Transactions for a UK-based online retailer (2010–2011)

Key Fields: CustomerID, InvoiceDate, InvoiceNo, Quantity, UnitPrice, Country

🛠️ Tools & Technologies
Python Libraries: pandas, numpy, matplotlib, seaborn

Power BI: Interactive dashboard creation

CSV Outputs:

RFM_Customer_Segmentation.csv → Customer-level data with RFM scores and segments

RFM_Segment_Summary.csv → Segment-level summary with average metrics & contribution %

📈 Project Workflow
Day 1 & 2 — RFM Calculation
Data cleaning & preparation

Calculation of Recency, Frequency, Monetary metrics

Assign R, F, M scores

Create combined RFM Score

Label customer segments using standard RFM mapping

Day 3 — Analysis & Dashboard
Segment-level summary:

Avg Recency, Frequency, Monetary

Customer count

% Monetary contribution

Python visualizations:

Monetary Contribution by Segment (Bar chart)

Customer Count by Segment (Bar chart)

Frequency vs Monetary Scatter Plot

Power BI dashboard build:

KPIs

Charts & filters

Interactive exploration

📊 Key Insights
Champions contribute the highest monetary value despite being fewer in number.

Loyal Customers have high purchase frequency but moderate spending.

Lost Customers are large in number but contribute minimal revenue.

Targeting high-contribution segments can yield better ROI.

📌 Deliverables
Python code for RFM calculation & analysis

Visual insights in Python

Power BI interactive dashboard

Clean datasets for further analysis

📬 Contact
For queries or collaboration:
Sameer — sameer.developer0001@gmail.com
