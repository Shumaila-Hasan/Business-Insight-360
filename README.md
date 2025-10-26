# Business-Insight-360

# Problem Statement

AtliQ relied on scattered Excel sheets for analytics, leading to slow decision-making and losses, especially during Latin American expansion. Competitors using advanced analytics gained an edge. The project aims to implement a centralized data analytics solution to improve transparency, efficiency, and strategic decision-making.

# Project Objective

Develop a comprehensive Power BI dashboard delivering actionable insights for Finance, Sales, Marketing, and Supply Chain, along with executive and key performer views, empowering stakeholders with data-driven decisions for growth and efficiency.

# Data Overview

Sources Provided:

3 Excel Files: Operating Expenses, Targets (FY 2022), Market Share (PC division)

2 SQL Databases:

gdb041: fact_sales_monthly, fact_forecast_monthly, dim_customer, dim_market, dim_product

gdb056: freight_cost, gross_price, manufacturing_cost, post_invoice_deductions, pre_invoice_deductions

Fiscal year: September to August, data span: Sep 2017 – Dec 2021

# Data Cleaning & Transformation

Removed spaces and standardized naming conventions.

Created dim_date for time-based analysis.

Merged sales & forecast tables into fact_actual_estimates.

Added calculated fields for deductions and optimized Power BI model by disabling unnecessary tables.

# Report Highlights

Dashboard: Executive, Finance, Sales, Marketing, Supply Chain, and Key Performer views

Data Model: Optimized for fast analysis

Tools Used: Power Query, Power BI, DAX


# Finance Insights

![ Finance Insights](https://github.com/Shumaila-Hasan/Business-Insight-360/blob/main/Finance%20View.png)


 Objectives

Improve financial planning, forecasting, and budgeting accuracy.

Monitor cost structures and enhance profitability tracking.

 Achievements

Built financial models for expense control and cost optimization.

Developed KPI-driven tracking for revenue and margin performance.

Delivered real-time budget vs. actual variance analysis for strategic review.

 #  Sales Performance

 ![Sales Performance](https://github.com/Shumaila-Hasan/Business-Insight-360/blob/main/Sales%20View.png)

 
 Objectives

Expand market reach and identify revenue growth opportunities.

Utilize customer insights to craft targeted sales strategies.

 Achievements

Created dynamic, interactive sales reports segmented by product, region, and customer type.

Implemented KPI dashboards to track customer retention and sales performance.

Highlighted top-performing customers and underperforming segments for actionable sales initiatives.

#  Supply Chain Optimization

 ![Supply Chain Optimization](https://github.com/Shumaila-Hasan/Business-Insight-360/blob/main/Supply%20Chain%20View.png)

 
 Objectives

Improve demand forecasting and optimize inventory planning.

Identify inefficiencies to strengthen supply chain reliability.

 Achievements

Analyzed forecast accuracy and demand–supply balance across regions.

Built supplier performance and logistics efficiency metrics to reduce stockouts and excess inventory.

Enabled data-backed decision-making for procurement and distribution planning.

#  Marketing Insights

![Marketing Insights](https://github.com/Shumaila-Hasan/Business-Insight-360/blob/main/Marketing%20View.png)


 Objectives

Strengthen brand visibility and improve customer engagement.

Optimize marketing spend using real-time campaign performance data.

 Achievements

Identified regional market trends and product performance drivers.

Provided data-driven segmentation and targeting recommendations.

Enhanced ROI measurement by linking campaign costs with revenue impact.

#  Executive Overview

![Executive Overview}()


 Objectives

Deliver an at-a-glance summary of overall business health.

Empower leaders to make data-backed, strategic decisions.

 Achievements

Developed an executive dashboard summarizing key business KPIs.

Visualized revenue, profit, and cost breakdowns across departments and regions.

Enabled drill-through navigation for deeper exploration of financial and operational data.

# Insights

Business Growth & Financial Performance:

Net Sales grew ~280% (FY19), ~140% (FY20), ~200% (FY21), ~350% (FY22)

Net Profit % negative since FY20 due to high operational & marketing costs

Revenue & Market Trends:

APAC largest market; Latin America smallest

Amazon top global customer; Nova smallest since FY20

Notebook segment: highest revenue growth but most negative Net Profit % in FY22

Desktop & Networking underperformed; USB flash drives declined FY21-FY22

Sales & Customer Insights:

Flat post-discounting model reduces gross margin; performance-based discounts recommended

Certain products had zero sales in FY22

Forecast & Supply Chain:

Forecast accuracy dropped from 86% (FY19) → 73% (FY20) → improved to 81% (FY22)

Excess inventory FY19–20; stock shortages FY21–22

Competitive Position:

PC market share grew 1% → 6% (FY21–22)

India fastest-growing market (~13% FY22)

Operational Insights:

Sales peak Sep–Dec (festive/year-end)

Retailers contributed ~72% of FY22 revenue

UK marketing spend highest; Germany low revenue, high marketing

# Recommendations

Gradually reduce operational & marketing expenses to improve Net Profit %.

Shift from flat discounts to performance-based model per product/customer.

Expand distribution & marketing in high-growth APAC markets.

Reevaluate pricing/cost of Notebook segment to improve profitability.

Investigate USB flash drives; reposition, discontinue, or upgrade models.

Improve customer forecasting using real-time data to reduce stock imbalances.

Increase market share in North America through targeted strategies.

Focus on product differentiation to compete with dominant players.

Optimize marketing spend in the UK and Germany.

Align inventory and promotions with Sep–Dec peak sales period.
