Loan Default Risk Dashboard (Power BI)

A 2-page interactive Power BI dashboard built to analyze loan default risk patterns across borrowers, loan purposes, interest rates, and time. This is my third Power BI project, focused on 
risk analytics in the banking and fintech domain.

Dashboard Preview

Link :-https://github.com/023kumar/SupplyChain-Analytics/blob/main/LoanDefault_Risk_Dashboard/Loan_default.pdf


📌 Project Overview

This dashboard helps identify which borrower segments, loan types, and interest rate bands carry the highest default risk — enabling data-driven decisions for credit risk management.

📈 Key Metrics
Metric	Value
Total Loans	601
Total Loan Amount	13M
Default Rate %	0.24%
% Borrowers with Defaults	0.28%
Average DTI Ratio	0.05K
Average Loan Amount	22.15K
Average Delinquency Days	27.04

📊 Pages & Visuals
Page 1 — Overview
Visual	Description
KPI Tiles	Interest Rate, Total Loan Amount, Total Loans, Default Rate
Donut Chart	Total loan amount by loan purpose
Bar Chart	Total loans by loan status (Current, Default, Paid Off, Late)
Line Chart	Total loan amount by month
Line Chart	Total loans count by month
Dropdown Slicers	Filter by Loan Purpose, Loan Status, Term Months

Page 2 — Default Deep Dive
Visual	Description
KPI Tiles	% Borrowers with Defaults, Avg DTI Ratio, Avg Loan Amount, Avg Delinquency Days
Scatter Plot	Loan amount vs interest rate, colored by default status (0/1)
Pie Chart	Total loans by loan purpose
Horizontal Bar Chart	Total defaults by loan purpose
Dropdown Slicers	Same filters consistent across both pages

✨ Key Features
2-page multi-report layout with consistent design and navigation
Cross-filtering interactivity — all visuals filter each other on click
Scatter plot for pattern detection — reveals default distribution across interest rate bands
Dropdown slicers for Loan Purpose, Status, and Term on both pages
Dark theme for professional presentation
Advanced DAX measures — DTI Ratio, Delinquency Days, % Borrowers with Defaults

🔍 Key Insights
Home Improvement and Wedding loans have the highest default counts (20 and 18 respectively)
Defaults are spread across all interest rate bands — not just high rates, as commonly assumed
Loan volume peaks in May–June and drops significantly from July onwards
Current loan status dominates (239) but Default (146) and Late (103) are concerning segments
DTI ratio and delinquency days are key early warning indicators for default risk

🛠️ Tools & Skills Used
Power BI Desktop — multi-page report design, DAX, data modeling
DAX — advanced measures (DTI Ratio, Delinquency Days, % Defaulters)
Scatter Plot Analysis — identifying default patterns across loan amount and interest rate
Risk Analytics — credit risk segmentation and default behavior analysis
UX Design — consistent slicer panel, dark theme, icon-based KPI cards

