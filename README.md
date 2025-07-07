# Vendor_Performance_Analysis
A data-driven analysis project to evaluate vendor performance, optimize inventory, and boost profitability using Python and Power BI.


📊 Vendor Performance Analysis-->
This project analyzes vendor and brand performance in a retail/wholesale environment by integrating purchase, sales, and freight data. Using Python, SQL, and Power BI, it identifies profitability drivers, evaluates vendor efficiency, and delivers actionable insights for inventory and vendor management.

🧠 Problem Statement-->
Retail and wholesale businesses often suffer from inefficient inventory turnover, vendor dependency, and unclear pricing strategies. This project aims to:

Identify underperforming brands.

Determine top-performing vendors by revenue and profit.

Analyze bulk purchasing benefits.

Assess inventory turnover and its financial impact.

Compare profit margins of vendors to inform pricing and marketing strategies.

📂 Project Structure-->

├── Exploratory Data Analysis.ipynb       # Initial data exploration and cleaning
├── Vendor Performance Analysis.ipynb     # Final analysis, visualizations, insights
├── get_vendor_summary.py                 # Merges tables, cleans data, and creates summary
├── ingestion_db.py                       # Loads raw CSVs into SQLite DB
├── vendor_sales_summary.csv              # Output of vendor performance metrics
├── vendor_performance.pbix               # Power BI dashboard for interactive visualization
├── Vendor Performance Report.pdf         # Final report with findings and recommendations
├── logs/                                 # Logging output for script monitoring
└── data/                                 # Folder for raw CSVs (used in ingestion script)

📈 Key Features-->

Automated Data Pipeline
From raw CSVs to a unified SQLite database.

Vendor Summary Generation
SQL queries merge freight, purchase, and sales data for in-depth analysis.

Data Cleaning & Feature Engineering
Including new KPIs: Gross Profit, Profit Margin, Stock Turnover, and Sales-to-Purchase Ratio.

Exploratory Analysis
Identifies negative margins, unsold inventory, and performance outliers.

Interactive Power BI Dashboard
Slice and dice vendor performance by brand, profitability, and more.

Actionable Insights Report
Vendor Performance Report.pdf presents key takeaways, charts, and strategic recommendations.

📊 KPIs & Metrics Computed-->

Gross Profit & Profit Margin

Total Sales and Purchase Dollars

Stock Turnover Ratio

Sales-to-Purchase Ratio

Vendor Contribution to Revenue

Impact of Bulk Buying

Low-performing vs. High-performing Vendor Comparison

 Insights & Findings-->

📌 Top 10 Vendors account for 65%+ of total purchases
📌 Bulk Purchasing reduces unit cost by up to 72%
📌 $2.71M Unsold Inventory tied to low-performing vendors
📌 Low Margin ≠ Low Profit: Some vendors have low sales but high margins
📌 Recommendations include pricing reevaluation, inventory optimization, and vendor diversification.

