# Power BI Report - Analysis and Auditing 

## Project Overview
**This interactive Power BI report is tailored to executives and provides insights to the processes of the company. This report is a one-stop shop with several dashboards, each with a different purpose including high level analyses, in depth analysis, and auditing.** I also designed this report to be user friendly so that anybody will be able to intuitively navigate it and find their desired insights. 

This report has data points which can be translated to several things based on the company and its industry. For example:
- Depending on the context, "issues" can represent "requests", "tasks", "cases", etc. Each "issue" has an "Open" or "Closed" status
- Depending on the context, "money" can be represent "revenue", "AUM", etc.
- Depending on the context, there is a "Type" column with three "Methods", and the "Methods" can represent different products/services, divisions of the company, delivery method, and more. For example, for a retail company, "methods" can be changed to represent their eCommerce vs. physical store data. 

I created the dummy data through Python. Dataset Features include:
- 1200 clients with a unique Client ID
- 10,000 "issues" with a unique Issue ID. 35% of issues have an Open status and 65% having a have status
- Countries with clients/issues: 50% in US, 20% in UK, 15% in Canada, and 15% distributed evenly amongst Germany, Grance, Australia, Japan, India, Brazil, and South Africa


There are **seperate but similar dashboards** within this report that analyze **either overall customer coverage or the "issues" data.** 

Software Used:
Power BI, Python, Excel

## High-Level Dashboards
I'll start by showcasing the dashboards that quickly provide high-level insights.

Below is the summary dashboard for CLIENT COVERAGE. It showcases key stats on the top, customer coverage by month, customers by coverage/issue type, clients by country, Money/Revenue by Country, and more. This is all interactive. For example, you can change the time frame or you can filter by a certain country by clicking on either the pie chart or matrix. 

![](images/BI_cust_summ.png)


Below is the summary dashboard for ISSUES. Similarly, It showcases key stats on the top, issues by month, issues by coverage/issue type, issues by country, and more. This is also all interactive.

![](images/BI_issue_summ.png)


Below is the dashboard with a map to visualize the global CLIENT COVERAGE. There are filters at the top to filter the time frame and the specific country. The map has bubbles that vary in size, which depends on the customer count for the country. If you select or hover over a specific country, there is a tooltip that appears with key KPIs.
![](images/BI_issue_map.png)
![](images/BI_cust_map_tip.png)

Below is the dashboard with a map to visualize the global ISSUES Similarly, there are filters at the top to filter the time frame and the specific country. The map's bubbles vary in size depending on the number of issues for the country. If you select or hover over a specific country, there is a tooltip that appears with key KPIs.

![](images/BI_issue_map_tip.png)








