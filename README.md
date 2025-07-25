Regional Sales Analysis Project 

This project focuses on analyzing retail sales performance across different regions using Python, Pandas, and visualization libraries like Matplotlib and Seaborn. The analysis is built on a multi-sheet Excel dataset where each sheet represents a different sales region. The main goal is to unify all data, perform end-to-end cleaning, and uncover insights that support better business decisions.

🎯 Objective
To consolidate region-wise Excel data and perform a comprehensive analysis of key business metrics like revenue, cost, profit, and profit margins. This project also demonstrates the ability to derive trends and visual summaries through Python-based tools and dashboards.

📁 Dataset Overview
File Name: Regional Sales Dataset.xlsx
Structure: Excel workbook with multiple sheets (each sheet = one region)
Each sheet includes:

order_number, order_date, channel

product_name, quantity, unit_price, revenue, cost

city_name, state_name, country, us_region, population

budget, total_cost, profit, profit_margin_pct

🧾 Files and Workflow
1. Regional Sales Dataset.xlsx
Purpose: Raw dataset with region-wise sales information in separate sheets.

Content: Contains customer orders, product info, financial metrics, and geography.

Why It Matters: Consolidation of this data is crucial to building a full business picture.

2. Data Loading & Preprocessing (Jupyter Notebook)
What It Does:

Reads all Excel sheets using pd.read_excel(..., sheet_name=None)

Merges all sheets into one unified DataFrame

Converts column formats (e.g., dates)

Handles missing values and calculates new metrics

Why It’s Important:

Ensures a clean, consistent dataset ready for analysis

Avoids data leakage and errors in later stages

3. Feature Engineering
New Fields Created:

total_cost = quantity * cost

profit = revenue - total_cost

profit_margin_pct = (profit / revenue) * 100

Extracted order_month_name and order_month_numz from dates

Why It’s Important:

Transforms raw figures into business KPIs

Enables more granular filtering and time-based insights

4. Data Exploration
Insights Extracted:

Top-performing products by revenue

Monthly revenue trends

Channel-wise revenue comparisons (Wholesale, Export, etc.)

Region and city revenue ranking

Profit margin analysis across products and locations

Why It’s Valuable:

Helps prioritize product focus, marketing efforts, and distribution strategies

5. Visualization with Matplotlib & Seaborn
Charts Included:

Bar charts (top cities by revenue)

Line charts (monthly revenue trends)

Pie charts (channel share)

Tree maps (product and city performance)

Heatmaps for region-wise revenue comparison

Why It Matters:

Transforms tabular data into visual insights

Supports strategic decisions with storytelling dashboards

🛠 Tools & Technologies Used
Tool	Purpose
Python	Main programming language
Pandas	Data cleaning, transformation, analysis
NumPy	Numerical operations
Matplotlib	Plotting static charts
Seaborn	Enhanced visualizations with statistical depth
Jupyter Notebook	Interactive data analysis
Excel	Original data source (multi-sheet)

📌 Project Workflow Summary
Import Data

Loaded all regional sheets into a unified pandas DataFrame.

Data Cleaning

Verified column types and handled missing/null values.

Calculated additional business KPIs (profit, cost, margin).

Exploratory Data Analysis (EDA)

Explored patterns in revenue, profit, churn by city, state, and product.

Visualized distributions and trends using bar and line plots.

Visualization

Built visual dashboards using Matplotlib and Seaborn.

Summarized performance by top regions, products, and channels.

👨‍💼 Key Business Insights
Top Revenue Cities: Help focus marketing and inventory in high-performing locations.

Sales Channel Analysis: Wholesale and Export channels dominate revenue share.

Month-on-Month Trends: Revealed seasonality and peak periods for demand.

Profit Margin Breakdown: Identified most and least profitable products by region.

Cost vs Revenue Alignment: Guided budget planning and operational efficiency.

📍 Skills Demonstrated
✅ Reading and merging multi-sheet Excel data
✅ Data cleaning and transformation using Pandas
✅ Creating custom business metrics (cost, profit, margin)
✅ Plotting meaningful visualizations using Matplotlib and Seaborn
✅ Drawing actionable insights from structured sales data
✅ Presenting clean, professional, and business-focused analysis

📬 Contact
LinkedIn: https://www.linkedin.com/in/syed-ibraheem-900b50222/
Email: syedibrahim1@gmail.com
