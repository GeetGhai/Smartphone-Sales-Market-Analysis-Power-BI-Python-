# Smartphone-Sales-Market-Analysis-Power-BI-Python-
End-to-end Smartphone Sales Analysis using Power BI + Python (EDA + Regression)
An end-to-end analytics project that analyzes smartphone sales data to understand brand performance, pricing impact, revenue drivers, and business trends. The project includes Python-based data cleaning + EDA + regression modeling and an interactive Power BI dashboard with KPIs, slicers, and navigation.

# Business Problem

The smartphone market is highly competitive. Businesses need to understand:

Which brands generate the highest revenue and profit?

Does pricing or quantity sold drive revenue more?

Which price segments contribute most to overall performance?

# Objectives

Analyze sales revenue, profit, and quantity sold across brands (2020–2025)

Identify key drivers influencing sales revenue

Segment products by price category (Mid → Super-Premium)

Build a Power BI dashboard for executive reporting & deep-dive analysis

Validate key drivers using a regression model (interpretable modeling)

# Dataset

Key columns used:

Brand, Year, OS

Price_USD, Quantity_Sold

Sales_Revenue, Profit, Rating

RAM_GB, Storage_GB, Battery_mAh, Screen_Size

# Tools & Skills Used

Power BI: KPI Cards, Slicers, Navigation Button, Trend charts, Brand comparison

Python: Pandas, NumPy, Matplotlib/Seaborn, data cleaning, EDA

Modeling: Multiple Linear Regression (interpretable insights)

# Project Workflow
1. Data Cleaning (Python)

Checked missing values & duplicates

Imputed numeric nulls using median

Corrected invalid OS records (Apple → iOS, others → Android)

Outlier handling using IQR method and replaced outliers with median

2. Feature Engineering

Created Price_Segment: Mid, Mid-Premium, Premium, Super-Premium

Aggregated brand-year performance for trend analysis

3. Exploratory Data Analysis (EDA)

Revenue trend by year and brand

Market share comparison by revenue

Price distribution by brand

Correlation analysis to identify key drivers

Price vs Quantity analysis to understand revenue behavior

4. Regression Modeling (Validation)

Built a Multiple Linear Regression model using:

Price_USD, Quantity_Sold → predict Sales_Revenue

Result: R² ≈ 0.79

Conclusion: Pricing and quantity sold are the strongest predictors of revenue

5. Power BI Dashboard

   ## 📊 Power BI Dashboard – Overview
   [![Smartphone Sales Dashboard Deep Dive](images/deep_dive_dashboard.png)](images/deep_dive_dashboard.png)


Dashboard includes:

Total Revenue, Total Profit, Total Quantity Sold, Profit Margin %

Sales Revenue by Year (trend)

Revenue by Brand (market share)

Revenue by Price Segment

Quantity Sold by OS

Brand summary table (Qty, Avg Price, Profit, Margin, Rating)

Navigation button: Go To Deep Dive

# Key Insights

Revenue is primarily driven by Price and Quantity Sold rather than technical specs

Super-Premium and Premium segments contribute significantly to total revenue

Brands show different strategies: premium pricing vs volume selling

OS split highlights Android dominance, with iOS concentrated under Apple

# Files in this Repository

dashboard/ → Power BI dashboard export (PDF / PBIT)

notebook/ → Python notebook (EDA + Regression)

images/ → Dashboard screenshots for quick viewing

reports/ → Project report PDF
