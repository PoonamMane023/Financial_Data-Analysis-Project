# 🚴 financial Analysis — Power BI Dashboard

## 📌 Overview
An interactive Power BI dashboard built on a bike store's MySQL sales dataset, 
designed to help business stakeholders track revenue trends, product performance, 
and year-over-year growth without needing to write SQL queries.

## 🎯 Business Problem
Retail sales teams often struggle to get quick, visual answers to questions like 
"How are we tracking this month vs. last year?" or "Which products are underperforming?" 
This dashboard consolidates raw transactional data into decision-ready visuals.

## 🛠️ Tools & Tech Stack
- **Database:** MySQL (source data extraction)
- **BI Tool:** Power BI
- **DAX Measures:** SUMX, CALCULATE, SAMEPERIODLASTYEAR, DATESMTD, ALLEXCEPT
- **Data Prep:** Power Query (transformations, cleaning)

## 📊 Key Features
- Month-to-date and year-over-year revenue comparisons
- Product-level performance breakdown (top/bottom sellers)
- Dynamic filtering by region, category, and time period
- Custom DAX measures for period-over-period growth analysis

## 🖼️ 
![Dashboard Screenshot](screenshots/dashboard-overview.png)
*(Add 2-3 screenshots or a short GIF walkthrough here)*

## 🔍 Key Insights
- [Insight 1 — e.g., "Identified a 15% dip in Q2 sales for [category], driven by..."]
- [Insight 2 — e.g., "Top 3 products account for X% of total revenue"]
- [Insight 3 — e.g., "Seasonal trend spike observed in [month]"]

## 📁 Repository Structure
├── data/              # Sample/sanitized dataset
├── screenshots/        # Dashboard preview images
├── dax-measures.md     #
