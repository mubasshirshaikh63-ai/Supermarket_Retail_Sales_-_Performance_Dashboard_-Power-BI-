# 🛒 Supermarket Retail Sales & Performance Dashboard (Power BI)
📌 Project Overview
This repository contains an end-to-end Retail Sales & Operational Performance Dashboard built using Microsoft Power BI. The dashboard delivers granular insights into retail transaction trends, profitability, geographical distribution (North America), brand-level metrics, and progress against business targets.

It serves as an executive reporting tool designed for store managers, inventory controllers, and regional directors to make data-backed commercial decisions.

🖼️ Dashboard Preview
<img width="1208" height="683" alt="Screenshot 2026-10-05 151917" src="https://github.com/user-attachments/assets/c61cb6a4-dde6-4326-8b5f-8d99dbf16118" />
















































































+---------------------------------------------------------------------------------------+
|  SUPERMARKET   |  [Transactions KPI]     [Profit KPI]          [Returns KPI]          |
|  PERFORMANCE   |  18,325 (+5.69%)        $71,682 (+5.61%)      496 (+2.90%)           |
+----------------+----------------------------------------------------------------------+
| [Brand Table]  | [Country Filter] | [Geographic Map]         | [Regional Treemap]     |
| Top brands,    | - Select All     | Cross-border footprint   | USA vs Mexico          |
| Profit margin, | - USA, Mexico,   | (North America stores)   | vs Canada              |
| Return rates   |   Canada         |                          |                        |
+----------------+------------------+--------------------------+------------------------+
|                | [Weekly Revenue Trending (Bar Chart)]       | [Revenue vs Target]    |
|                | Fiscal year quarterly & seasonal movement   | Gauge Visual ($120.1K) |
+----------------+---------------------------------------------+------------------------+


🎯 Key Metrics & KPIs Tracked
Metric	Overall Value	Current Month Actual	Target / Goal	Variance
Total Transactions	167,616	18,325	17,339	+5.69%
Total Net Profit	$661,159	$71,682	$67,871.78	+5.61%
Returns Volume	—	496	482	+2.90%
Average Margin	~60%	—	—	Healthy
Revenue vs Target	$120,160.84	Target: $119,477.23	Target Achieved ✅

🔍 Key Dashboard Features
Executive KPI Cards with Sparklines:

Real-time tracking of current month Transactions, Profit, and Returns with target benchmarks.

Brand & Product Matrix:

Conditional formatting on Profit Margins (highlighting top margins like Plato at 64%).

Critical risk alerts on Return Rates (highlighting problematic brands like Horatio in red).

Interactive Geographic Analytics:

Map Visual displaying regional store locations across the USA, Mexico, and Canada.

Treemap breaking down market share by country.

Temporal Revenue Trending:

Weekly sales distribution highlighting seasonality and mid-year volume surges.

Target Achievement Gauge:

Real-time gauge visual monitoring current revenue against assigned target thresholds.

💡 Business Insights & Strategic Findings
USA Market Lead & Month Variance: While the United States remains the primary volume driver, its current month transactions sat -5.73% below target, cushioned by strong demand in Mexico and Canada.

Margin Stars: Brands such as Plato (64%), BBB Best (62%), and Imagine (62%) produce the highest margins and warrant prime shelf real estate.

Return Rate Optimization: The brand Horatio exhibited an anomalous return rate flag; inventory batch inspection and vendor quality checks are recommended.

🛠️ Tech Stack & Tools
Business Intelligence Tool: Microsoft Power BI Desktop & Service

Data Modeling: Star Schema / Snowflake relational modeling

Calculation Engine: DAX (Data Analysis Expressions) for calculated measures, variances, and dynamic KPI states

Data Prep & ETL: Power Query (M Language)

📂 Repository Structure
Plaintext
├── assets/                  # Dashboard screenshots and demo GIFs
│   ├── overview.png
│   └── regional_slices.png
├── data/                    # Sample / anonymized datasets (CSV/Excel)
├── reports/                 # Executive summary & PDF exports
│   └── Supermarket_Performance_Report.md
├── Supermarket_Sales.pbix   # Main Power BI project file
└── README.md                # Project documentation
