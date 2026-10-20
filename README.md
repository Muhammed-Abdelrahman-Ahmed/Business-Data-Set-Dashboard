# Business-Data-Set-Dashboard
A complete Excel data analysis project investigating sales performance and order returns through a dual dashboards: an Executive Overview and an Operations Diagnostic view

### 📅 Project Timeline
* **Development Period:** October 2026 .
* **Note:** This project was developed locally and later migrated to GitHub .

The main objective was to evaluate both sales performance and the dynamics behind product returns. The final output includes two desktop-optimized dashboards (16:9 aspect ratio) designed to provide both strategic insights for executives and actionable diagnostic data for the operations team.

## Tools I Used
- Microsoft Excel
- Power Query
- Power Pivot

## Project Workflow
Here is how I approached the analysis, from raw data to actionable insights:

1. Data Preparation and Cleaning
I started by importing multiple datasets (Business Data, Returns, People, Orders, and Shipping Costs) into Power Query. I cleaned the data and ensured everything was properly formatted to build a reliable foundation.

2. Defining the Scope
Based on the data, I defined the scope of the analysis to cover salespersons' performance, return rates, regional differences, shipment modes, customer segments, and product profitability[cite: 17]. 

3. Data Modeling
Using Power Pivot, I built a relational data model connecting the Orders table with Returns, People, and Shipping Costs. I created custom DAX measures to calculate KPIs like Total Sales Without Returns, Profit Margins, and Total Returned Value[cite: 15, 17].

4. Diagnostic Analysis (Finding the "Why")
Before building the dashboards, I dug deep into the data to understand the underlying issues[cite: 17]. For example, I discovered that profitability drops into a financial loss when discount rates exceed 20%. I also identified a major issue in the West region, where a single salesperson (Anna Andreadi) was linked to over 61% of all returned orders, particularly in the Binders and Paper sub-categories.

5. Designing the Desktop Dashboards
I built two separate dashboards optimized for a 16:9 desktop view:

- **Executive Sales & Profitability Overview:** This macro-level dashboard is for high-level decision-making. It highlights total sales ($2.1M+), total profit, and a clear 5.9% return rate. It also visualizes sales trends from 2014-2017 and compares performance across customer segments (with Consumer being the most profitable)[cite: 13, 17].

- **Operations & Sales Performance Diagnostics:** This micro-level dashboard is for the operations team. It tracks detailed metrics like Average Order Value, Average Shipping Period (4 days), and highlights the most/least profitable products. Importantly, it visualizes the returned orders across regions, pointing directly to the problem areas identified during the diagnostic phase[cite: 14, 17].

## Key Recommendations
Based on the analysis, a few immediate actions are recommended: cap discounts at 20%, investigate the high return rate linked to specific sales behaviors in the West region, and focus marketing efforts on the highly profitable Copiers and Phones categories[cite: 17].

## Exploring the Dashboards
Download the Excel file and open it on your desktop. You can switch between the Executive and Operations tabs and use the slicers to filter by Region, Category, and Order Date.
