# Enterprise-Intelligence-Budget-Analytics-Dashboard
**DESCRIPTION**

This GitHub repository contains a complete Budget Analytics Dashboard built with Power BI Desktop, powered by a Python data generation pipeline. The project demonstrates end-to-end analytics capabilities including data generation, visualization, and business intelligence without requiring database infrastructure.

**Quick Facts**
**Dashboard Pages**: 3 interactive Power BI dashboards covering Budget Summary, Department Spend & Cost, and Revenue/ROI Analysis

**Data Volume**: 50,000+ records generated via Python pipeline

**Technology Stack**: Power BI Desktop, Python (Faker, Pandas), CSV data exports

**Key Metrics**: $149M Total Budget, $161M Actual Spend, 108.4% Budget Utilization, 93.4% Average ROI

**Analysis Depth**: Variance analysis, trend forecasting, department performance, campaign ROI comparison

---

**Business Problem**

**Multiple CSV Files & Data Fragmentation**
Budget data scattered across 6+ separate CSV files (departments.csv, budgets.csv, actual_spend.csv, campaigns.csv) with no centralized system, making it impossible to correlate budget allocations with actual spending or campaign performance in a unified view.

**Messy & Inconsistent Data & No Budget Tracking Capability**
Raw data contains inconsistent formatting, missing values, duplicate records, and conflicting values across files (e.g., same department with different budget amounts in different files), requiring extensive manual cleanup before any analysis could be performed.Organization cannot track real-time budget vs. actual spend variances across departments and months, leading to blind spots on overspending (discovered later to be $12M/8.4% over budget) and inability to take corrective action until damage is done.

**No Professional Reporting Infrastructure**
Organization lacks formal reporting structure for communicating budget performance to executives, department heads, and finance teams, resulting in inconsistent insights, missed insights, and inability to support data-driven budget decisions.All data trapped in raw CSV format with no dashboards, charts, or visual analytics—stakeholders forced to manually open Excel spreadsheets, copy/paste data, and create ad-hoc pivot tables to answer basic questions about budget status.

**Department Performance Visibility Gap & Campaign ROI Blindness**
Finance and department heads cannot see which departments are exceeding budgets, by how much, or why—preventing proactive cost control and accountability measures despite organization-wide overspending.Marketing spend tracked separately from revenue generated, making it impossible to correlate campaign investments with actual returns or optimize marketing budget allocation based on performance data.

---

**Key Metrics**

**Budget Summary**
•	Total Budget Allocated: $149M across all departments
•	Total Actual Spend: $161M (over budget by $12M)
•	Budget Variance: $12M overage (8% over allocated budget)
•	Budget Utilization: 108.4% (departments spending more than planned)
•	Remaining Budget: -$12M (deficit position)
•	Department Performance: Color-coded status showing which departments are over/under budget
•	Monthly Trend Analysis: Budget vs. actual spend tracking across 24-month period with variance indicators


**Department Spend & Cost Analysis**
•	Overbudget Departments: 6 departments exceeding allocated budgets
•	Average Utilization Rate: 108.4% (showing organization-wide overspending)
•	Total Department Spend: $161M distributed across Finance, Marketing, HR, Sales, Operations, and IT
•	Highest Monthly Spend: $11M (Marketing department in peak month)
•	Cost as % of Revenue: 129.1% (spending exceeds revenue generation)
•	Top 5 Spenders: Rankings showing Marketing ($47M), Finance ($43M), Sales ($42M) leading spend
•	Budget vs Actual by Department: Side-by-side comparison showing variance magnitude for each department
•	% Budget Used by Department: Utilization percentages (Marketing 113.1%, Finance 114.2%, HR 111.0%)

 
 **Revenue, ROI & Forecast Analysis**
•	Total Campaign Revenue: $39M generated from campaigns
•	Average ROI: 93.4% across all campaigns
•	Campaign Efficiency: 4.9% conversion rate indicating campaign performance
•	Total Ad Spend: $2M invested in paid advertising
•	Sum of Revenue by Campaign: Complete revenue contribution by campaign name
•	Campaign ROI Comparison: Detailed comparison showing which campaigns deliver highest ROI
•	Total Ad Spend & Revenue by Campaign: Spend efficiency analysis identifying highest-performing campaigns
•	Revenue vs Net Income Over Time: Trend line showing revenue stability and net income tracking from 2021-2024
•	Quarterly Performance: Q1-Q4 breakdown across fiscal years with growth trajectory


