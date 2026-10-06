# 🛒 Supermarket Retail Sales & Performance Dashboard (Power BI)
📌 Project Overview
This repository contains an end-to-end Retail Sales & Operational Performance Dashboard built using Microsoft Power BI. The dashboard delivers granular insights into retail transaction trends, profitability, geographical distribution (North America), brand-level metrics, and progress against business targets.

It serves as an executive reporting tool designed for store managers, inventory controllers, and regional directors to make data-backed commercial decisions.

🖼️ Dashboard Preview
<img width="1208" height="683" alt="Screenshot 2026-10-05 151917" src="https://github.com/user-attachments/assets/c61cb6a4-dde6-4326-8b5f-8d99dbf16118" />


SUPERMARKET PERFORMANCE & ANALYTICS REPORT

Business Analyst & Executive Management Review

EXECUTIVE SUMMARY

Total Revenue vs Target:
Total recorded revenue reached $120,160.84 against a target milestone of $119,477.23, achieving a 100.57% goal attainment rate. Core financial targets have been successfully exceeded.

Volume and Profit Performance:
Current month transactions closed at 18,325, outperforming the monthly goal of 17,339 by +5.69%. Current month profit reached $71,682, surpassing the target of $67,871.78 by +5.61%.

Portfolio Quality and Health:
Current month returns totaled 496 units, running +2.90% above the target threshold of 482. However, the overall return rate remains controlled at 1.0% (0.01), and the overall profit margin stays healthy at 60.0% (0.60).

KEY PERFORMANCE INDICATORS (DETAILED METRICS)
Current Month Transactions:

Actual: 18,325
Target: 17,339
Variance: +5.69% (Above Goal)
Analysis: Strong footfall and sustained sales velocity across active channels.
Current Month Profit:
Actual: $71,682
Target: $67,871.78
Variance: +5.61% (Above Goal)
Analysis: Bottom-line expansion supported by favorable high-margin product mix.
Current Month Returns:
Actual: 496 units
Target: 482 units
Variance: +2.90% (Over Threshold)
Analysis: Marginal increase alongside transaction growth; requires category tracking.
Revenue vs Benchmark Target:
Actual: $120,160.84
Target: $119,477.23
Variance: +0.57% (Quota Met)
Analysis: Target achieved across key operating territories.
Operational Margin and Return Rate:
Overall Profit Margin: 60.0% (Stable baseline)
Overall Return Rate: 1.0% (Controlled risk level)

GEOGRAPHIC & REGIONAL BREAKDOWN
United States (USA):

Acts as the primary revenue engine and holds the largest market share.
Accounts for over 112,405 transactions and $440,116 in cumulative profit.
Strong geographic concentration in West Coast, Central, and Northeast retail clusters.

Mexico:
Represents the second-largest geographic footprint.
Demonstrates consistent customer transaction frequency and reliable regional contribution.

Canada:
Shows the lowest market share and transaction density.
Represents an untapped growth opportunity requiring localized customer acquisition campaigns.

BRAND & PRODUCT PORTFOLIO PERFORMANCE
High-Volume Core Contributors:
Hermanos: Top brand overall with 8,071 transactions, $33,167 in profit, and 59% margin.
Tell Tale: Strong volume driver with 7,694 transactions, $29,926 in profit, and 58% margin.
Ebony: High performer with 7,685 transactions, $29,749 in profit, and 60% margin.
Tri-State: Stable performer with 7,438 transactions, $29,065 in profit, and 59% margin.
High-Margin Strategic Brands:
Plato: 4,912 transactions, $18,503 profit, delivering an industry-leading 64% margin.
Cormorant: 5,382 transactions, $22,502 profit, delivering a 62% margin.
BBB Best: 5,254 transactions, $19,375 profit, delivering a 62% margin.
Trailing and Margin-Sensitive Brands:
Better: Lowest sales velocity with 4,073 transactions and $13,193 profit at 61% margin.
CDR: Lower volume tier with 4,574 transactions and $18,008 profit at 59% margin.
Horatio: Generated 6,121 transactions and $25,589 profit, but has a 58% margin and elevated return flags.

REVENUE TRENDS & SEASONALITY

Cyclical Volume Spikes:
Weekly volume repeatedly exceeds 4,000 transactions in early Q1 (January/February),
mid-Q2 (April/May), and early Q3 (July).
Mid-Quarter Contraction:
Sales volume shows consistent dips between major promotional cycles, indicating
heavy reliance on event-driven retail pushes rather than steady baseline run-rate.
STRATEGIC BUSINESS RECOMMENDATIONS
Merchandising & Shelf-Space Allocation:
Expand shelf visibility and cross-selling promotions for high-margin brands like
Plato (64%), Cormorant (62%), and BBB Best (62%) to maximize ticket profitability.

Regional Diversification:
Deploy targeted marketing and logistics partnerships in Canada to lower dependency
on the US domestic market and unlock regional growth.
Inventory & SKU Rationalization:
Conduct an ABC inventory turnover analysis on slow-velocity brands such as Better
and Landslide to minimize warehouse carrying costs.
Return Rate Root-Cause Analysis:
Perform SKU-level audits on items exceeding return thresholds (+2.90%) to detect
packaging flaws, sizing discrepancies, or supplier quality issues.

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
