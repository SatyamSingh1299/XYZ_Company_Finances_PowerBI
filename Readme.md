# XYZ Company Financial Performance Dashboard (Power BI)

This repository contains a Power BI report that analyzes XYZ Company’s revenue and profitability over time to identify trends, cost inefficiencies, and opportunities for revenue growth.

## Problem Statement

Develop methods to analyze trends, identify cost inefficiencies, and pinpoint areas for revenue growth that will enable a deeper understanding of XYZ company’s operational health.

The dashboard is designed to answer the following questions:

1. What is XYZ company’s total revenue year‑to‑date (YTD) compared to last year?  
2. Has there been a growth or decline in revenue for a specific country or region this quarter?  
3. Have there been any significant changes in operating expenses compared to the budget?  
4. What is XYZ company’s current profit margin?  
5. By how much did sales increase from February to March this year?  
6. What was the lowest point in sales for 2020?  
7. Is there a specific quarter that historically generates the most sales?  
8. By what percentage did Q2 sales contribute to the total sales in 2020?  

## Dataset

- **Time period:** 2018–2020 (with YTD and year‑over‑year views).  
- **Grain:** Financials summarized by year and quarter.  
- **Key fields:** Revenue, Cost of Sales, Operating Expenses, Depreciation & Amortization, Non‑operating items, Interest & Tax, Net Profit, Country, Year, Quarter.  
- **Main metrics calculated:**  
  - Sales Revenue  
  - Gross Profit  
  - EBITDA  
  - Operating Profit  
  - PBIT  
  - Net Profit  

## Report Pages & Visuals

### 1. Sales & Profit Overview

- Matrix of income statement lines (Trading account, Operating Expenses, Non‑operating, Interest & Tax) across 2018, 2019, 2020.  
- KPI cards for:
  - **Sales Revenue YTD**  
  - **Sales FTP** (total sales for the period)  
  - **Gross Profit**, **EBITDA**, **Operating Profit**, **PBIT**, **Net Profit** by year.  
- Line charts for:
  - Sales Revenue trend by year  
  - Gross Profit trend (2018–2020)  
  - Net Profit trend by quarter across years.  
- Slicers for **Country** and **Year** to compare geographies and time periods interactively.

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/XYZ_Company_Finances_PowerBI/blob/main/images/img1.png" /></a></p>  


<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/XYZ_Company_Finances_PowerBI/blob/main/images/img2.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/XYZ_Company_Finances_PowerBI/blob/main/images/img3.png" /></a></p>  


## Techniques & Skills Demonstrated

- Data modeling and measure creation for financial statements in Power BI.  
- DAX time‑intelligence for YTD, prior year comparison, and variance calculations.  
- KPI, matrix, and line‑chart visuals for multi‑year financial analysis.  
- Interactive analysis using country and year slicers to explore regional performance.  

## Files in This Repository

- `XYZ_Financial_Dashboard.pbix` – Main Power BI report.  
- `images/financial_dashboard_overview.png` – Screenshot of the dashboard.  
- `README.md` – Project documentation (this file).  

