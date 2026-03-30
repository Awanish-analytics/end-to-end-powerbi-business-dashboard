# end-to-end-powerbi-business-dashboard
End-to-end Power BI dashboard project analyzing lead conversion, revenue, pricing, and business performance using advanced SQL and data modeling.

📊 End-to-End Power BI Business Dashboard
🔍 Project Overview

This project is a complete Business Intelligence solution built using SQL and Power BI to analyze:

Lead conversion performance
Revenue & financial health
Pricing and costing insights
Discontinued leads analysis
Franchise compliance tracking

The dashboard helps stakeholders make data-driven decisions by tracking performance across multiple business units (REFRESH & ZONES).

🛠️ Tech Stack
SQL (PostgreSQL) – Data extraction & transformation
Power BI – Data visualization & dashboarding
DAX – Measures and calculations
Data Modeling – Star schema & relationships
📁 Dashboard Pages
1️⃣ Overview Dashboard
Total leads, active, completed & discontinued
Lead distribution by stage
Referral source analysis
Monthly trends
Conversion benchmarking (Top vs Bottom quartile)
2️⃣ Financial Dashboard
Annual revenue vs actual revenue
Revenue difference analysis
Marketing spend tracking
Cost per lead
XERO integration insights
3️⃣ Pricing Dashboard
Count of approved pricing
Pricing distribution across stages
Organisation-level pricing insights
4️⃣ Discontinued Leads Analysis
Monthly discontinued trends
Reasons for lead drop-off
Business improvement insights
🧠 Key Features & Logic
🔹 Conversion Rate Calculation
Based on lead distribution per stage
Uses window functions in SQL
🔹 Quartile Benchmarking
Top 25% vs Bottom 25% performance
Implemented using:
PERCENT_RANK()
Window partitions (Global & Country level)
🔹 Stage Standardization
Different business stages (REFRESH vs ZONES) mapped into a common funnel
📂 SQL Highlights
1. Lead Conversion & Benchmarking
Complex CTE-based query
Calculates:
Lead counts
Conversion rates
Global & country quartiles
2. Deal Status Summary
Active / Hold / Completed deals
3. XERO Invoice Compliance
Tracks:
Invoices sent via control system
Compliance status
4. Revenue Analysis
Minimum vs actual revenue
Marketing spend comparison
5. Lead Funnel Analysis
Latest stage tracking
Referral & discontinuation insights
6. Pricing Analysis
Pricing vs costing linkage
Revenue breakdown per deal
