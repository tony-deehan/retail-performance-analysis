# Retail / E-Commerce Performance Analysis
### Superstore Dataset | Sales, Profitability & Discount Impact

---

## Project Overview

This project analyses retail performance to understand how sales, profitability, and discounting interact across product categories.

The objective was to identify why increasing sales do not always lead to higher profitability and uncover the role discounting plays in driving margin performance.

---

## Business Questions

- How have sales and profit trended over time?
- Are higher sales translating into higher profitability?
- How does discounting impact profit margins?
- Which product categories perform best in terms of revenue and profit?
- Are certain categories more reliant on discounting than others?

---

## Data Source

Dataset:  
Superstore Retail Dataset (2014–2017)

The dataset contains transactional order-level data across multiple product categories.

Each row represents a single order and includes:

- Sales
- Profit
- Profit Margin
- Discount
- Category
- Order Date

---

## Methodology

### 1. Data Exploration (Python)

Initial data exploration was conducted in Python to:

- Understand distributions of key variables
- Identify outliers and skewed behaviour
- Explore relationships between discount and profit margin

---

### 2. Data Preparation

Key fields were validated and used directly for analysis:

Profit Margin
```
Profit ÷ Sales
```

Discount
```
Percentage reduction applied per order
```

---

### 3. Analysis Approach

The analysis focused on three core areas:

- **Trend Analysis** → understanding how sales and profit evolve over time  
- **Category Performance** → comparing revenue and profitability across product groups  
- **Discount Impact** → evaluating how discounting affects profit margins  

---

## Key Findings

- Sales show a consistent upward trend over time.
- Profit is more volatile and does not consistently follow sales growth.
- Higher sales do not always translate into higher profitability.
- Discounting has a clear negative impact on profit margins.
- Furniture is the most affected category, showing significant margin decline with increased discounting.
- Discounting is widely used across all categories, indicating a systemic reliance on price reductions.

---

## Strategic Recommendations

### Reduce High Discount Levels
Limit excessive discounting, particularly where it results in negative margins.

### Improve Furniture Profitability
Review pricing and cost structures to address low-margin performance in Furniture.

### Focus on High-Performing Categories
Invest in categories like Technology that deliver stronger profitability.

### Monitor Profit Alongside Sales
Shift focus from revenue-only metrics to include profit margin tracking.

### Test Alternative Strategies
Use targeted promotions instead of broad discounting to protect margins.

---

## Visualisation

The interactive dashboard was built in Tableau Public.

View Interactive Dashboard:  
https://public.tableau.com/views/RetailE-CommercePerformance/RetailPerformanceOverview

---

## Tools and Technologies

- Python — Data exploration and analysis  
- Tableau Public — Data visualisation and dashboard creation  
- Google Sheets — Data inspection and validation  
- Google Slides — Stakeholder presentation  

---

## Project Structure

```
retail-performance-analysis/
│
├── assets/          # Dashboard images
├── data/            # Dataset (if included)
├── notebooks/       # Python analysis
├── slides/          # Final presentation (PDF)
└── README.md
```

---

## What This Project Demonstrates

- Translating business problems into analytical questions
- Exploring datasets using Python
- Identifying relationships between variables (discount vs profit)
- Building clear and effective Tableau dashboards
- Communicating insights in a business-focused way
- Delivering actionable recommendations based on data

---

## Notes

This project uses a publicly available retail dataset for portfolio purposes.

All analysis and insights were developed independently to demonstrate end-to-end data analysis skills.
