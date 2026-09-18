Sales Data Cleaning & Dashboard

Excel project focused on cleaning a messy raw sales export and building an interactive dashboard to summarize key business metrics.

Overview

This project simulates a common real-world analyst task: taking a raw, inconsistent data export and turning it into something clean and analysis-ready. The dataset intentionally included a range of data quality issues, inconsistent text formatting, mixed date formats, numbers stored as text, duplicate rows, and missing values. So I could practice identifying and resolving each type of problem before building a dashboard on top of the cleaned data.

Tools Used
Excel — data cleaning, formulas, and dashboard/visualization
Data Source

A synthetic sales dataset (186 rows), generated with AI assistance to include realistic data quality issues (inconsistent formatting, mixed date formats, duplicates, missing values) for the purpose of practicing Excel data cleaning techniques.

The Challenge

The raw export included:

Inconsistent customer name and product formatting
Mixed casing across category, region, and status fields
Numbers stored as text
Three different date formats within a single column
Duplicate order rows
Scattered missing values
What I Did
Standardized text formatting (names, products, categories) using TRIM and PROPER
Converted text-formatted numbers and mixed-format dates into usable values, with error-handling for edge cases
Removed exact duplicate orders while preserving legitimate repeat purchases
Identified and removed a stray non-data row and one fully blank row
Verified the final row count (180) against the original (186) to confirm nothing was lost incorrectly
Built pivot tables to summarize revenue and order counts by category, region, status, and month

What I Delivered
A cleaned, analysis-ready dataset plus an interactive dashboard featuring:
KPI summaries: 
total revenue, total orders, average order value
Filterable slicers by category, status, and date
Visual breakdowns of revenue by region, product, and category
Written key insights summarizing the findings

Key Insights
May had the highest monthly revenue ($1,164.09), while September recorded the lowest at $54.72.
Shipped orders account for the largest share of both orders and revenue, generating $2,473.91 from 77 orders. Cancelled orders were the smallest contributor, with $1,231.77 in revenue from 47 orders.
Ceramic Mug was the top revenue-generating product at $908.16, followed by Desk Lamp ($740.16) and Throw Pillow ($565.14), revenue was concentrated among a few top-performing products.
West was the strongest-performing region, generating $1,334.73, while the South region had the lowest revenue at $783.35.

<img width="866" height="1162" alt="Sales_Dashboard" src="https://github.com/user-attachments/assets/f99c0f99-6e90-43cd-aca7-ab97b3703891" />

Files in This Repo
Messy_Sales_Data_Final.xlsx — raw and cleaned data plus the dashboard
README.md — project overview (this file)
