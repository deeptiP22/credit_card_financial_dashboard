# credit_card_financial_dashboard
Power bi dashboard
Project Objective
The goal of this dashboard is to analyze credit card transaction and revenue data to help a financial institution understand customer spending behavior, identify high-value customer segments, and track revenue performance across quarters — enabling data-driven decisions around targeting, retention, and product strategy.

Steps
Data collection & modeling — Combined multiple source tables (credit_card.csv, customer.csv, cc_add.csv, cust_add.csv) into a relational data model, linking transactions to customer demographics and job categories.
Data cleaning (Power Query) — Handled date format mismatches, removed duplicates, and standardized categorical fields (e.g., customer job types).
DAX measures — Built measures for Sum of Total Revenue, Sum of Total Transaction Count, and quarter-over-quarter comparisons.
Visualization — Designed a combo chart (bar + line) to show Quarterly Revenue against Transaction Count trends, and a column chart to break down Revenue by Customer Job.
Interactivity — Added a Week_Start_Date slicer so users can filter the entire report dynamically by week.
Deployment — Published the report and exported a PDF snapshot to GitHub for portfolio sharing.
Insights
Revenue dipped in Q2 (13.8M) after a stronger Q1 (14.0M), before recovering through Q3 (14.2M) and dropping again in Q4 (13.3M) — suggesting a seasonal pattern worth investigating further.
Transaction count and revenue move somewhat inversely in places (e.g., Q4 shows the highest transaction count at 161.6K but the lowest revenue) — this could indicate a shift toward smaller-ticket purchases, worth flagging for the business.
Businessmen are the top revenue segment by far (~17M), nearly double the next-highest group (White-collar, ~10M) — a strong candidate for a priority customer segment.
Revenue drops fairly evenly across White-collar, Blue-collar, and Govt segments (10M, 8M, 8M) before falling off further for the remaining categories, with Retirees contributing the least (~5M).


