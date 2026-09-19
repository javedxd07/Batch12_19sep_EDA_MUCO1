# Category Intelligence — Retail Product Performance EDA

## Overview

This project is part of the **Calibo AI Academy – Phase 1, Mini Use Case 01**. It focuses on analysing retail sales data to understand category performance, product performance, discount effectiveness, and sales patterns.

The analysis is designed to help a Category Manager make data-driven decisions for an upcoming supplier review.

## Business Context

The dataset represents a regional retail chain with:

- 12 stores across 6 cities in Andhra Pradesh
- 5 product categories
- 25 products
- 107,836 transactions
- ₹45.98 Cr total revenue
- Sales data from January to June 2026

### Categories

- Electronics
- Apparel
- Grocery
- Home & Kitchen
- Personal Care

## Business Question

Which categories and products are driving performance, where are declines occurring, and what should the Category Manager prioritise for the supplier review?

## Objectives

1. Analyse monthly revenue trends across all categories.
2. Identify the top 2 and bottom 2 products in each category.
3. Evaluate the effectiveness of different discount levels.
4. Identify day-of-week and monthly sales patterns.
5. Provide data-backed insights for the Category Manager.

📊 Project Workflow
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Pattern & Relationship Analysis
     ↓
Key Insights
     ↓
Summary & Presentation

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset

The dataset contains:

- Transaction ID
- Date
- Store ID
- Store City
- Category
- Product Name
- Units Sold
- Unit Price
- Revenue
- Discount %

The dataset contains **107,836 transactions**, with **0 null values** and **0 duplicate transaction IDs**.

## Analysis

### Category Revenue Trends

Electronics showed the steepest decline:

- January: ₹4.57 Cr
- June: ₹2.97 Cr
- Change: **−35.02%**

Apparel showed the strongest growth:

- January: ₹1.00 Cr
- June: ₹1.35 Cr
- Change: **+34.10%**

Grocery was the most consistent category, with a coefficient of variation of **3.87%**.

### Product-Level Performance

The top 2 and bottom 2 products were identified for each category.

A key finding was that there was no extremely weak product. The weakest products still generated approximately **88–98%** of the revenue of the strongest products within their categories.

In Electronics:

- Headphones: ₹4.77 Cr
- Laptop: ₹4.66 Cr
- Tablet: ₹4.47 Cr
- Smart TV: ₹4.19 Cr

This indicates a broader category-level issue rather than a single product problem.

### Discount Effectiveness

Average revenue per transaction decreased from **₹4,685.65 at 0% discount to ₹3,631.73 at 20% discount**, while average units sold remained almost flat at **2.57–2.60 units**.

The dataset does not contain cost or margin information, so the exact margin impact of discounts cannot be measured.

### Sales Patterns

- Best day: **Saturday — ₹35.24L average daily revenue**
- Worst day: **Monday — ₹20.12L average daily revenue**
- Best month: **January — ₹8.48 Cr**
- Worst month: **June — ₹6.93 Cr**

## Key Insights

- Apparel showed the strongest growth during the analysis period.
- Electronics experienced the steepest decline.
- Electronics generated ₹22.65 Cr but declined by 35.02%.
- No single product was identified as a clear underperformer requiring delisting.
- Higher discounts did not result in a meaningful increase in units sold.
- Product-level cost or margin data would be useful for making a final investment or shelf-space decision.

## Team

| Member | Role | Contribution |
|---|---|---|
| Mulla Javeed | Product Insights Analyst | Top & Bottom Product Analysis |
| Vikas | Discount & Pattern Analyst | Discount Effectiveness & Sales Patterns |
| Ashok | Business Synthesis Analyst | Category Manager Briefing |
| Geetha | Data Analyst | CBIM, Data Inspection & Category Revenue Trends |
