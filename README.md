# Business Sales Performance Analytics

## Future Interns – Data Science & Analytics Task 1

This project analyzes Superstore sales data to identify sales trends, product performance, category performance, regional performance, and profitability patterns.

The goal is to transform raw sales data into meaningful business insights and actionable recommendations using Python and Tableau.

---

## Project Objectives

- Clean and organize the sales dataset
- Analyze revenue trends over time
- Identify top-performing products
- Analyze category and regional performance
- Evaluate profitability and discount patterns
- Identify loss-making products
- Build an interactive business dashboard
- Provide actionable business recommendations

---

## Dataset

**Dataset:** Sample Superstore Sales Dataset

- Rows: 9,994
- Columns: 21
- Date Range: 2014–2017
- Categories: Furniture, Office Supplies, Technology
- Regions: West, East, Central, South

---

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Tableau
- GitHub

---

## Key Business KPIs

| KPI | Value |
|---|---:|
| Total Sales | $2.297M |
| Total Profit | $286.4K |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Total Customers | 793 |

---

## Key Insights

### Sales Trends
- Sales increased strongly after 2015.
- 2016 recorded approximately 29.47% sales growth.
- 2017 recorded approximately 20.36% sales growth.
- November 2017 recorded the highest monthly sales.

### Category Performance
- Technology generated the highest sales and profit.
- Office Supplies recorded the highest quantity sold.
- Furniture generated significant sales but had a relatively low profit margin.

### Regional Performance
- West was the strongest region in both sales and profit.
- East was the second-highest performing region.
- Central had the lowest profit margin among the four regions.

### Product Performance
- Canon imageCLASS 2200 Advanced Copier was the highest-selling product.
- Several products generated high sales but low or negative profit.
- 301 products were identified as loss-making.

### Discount & Profitability
Higher discount levels were strongly associated with declining profitability in the dataset.

This analysis identifies an association rather than proving that discounts directly cause losses.

---

## Dashboard

The Tableau dashboard includes:

- KPI Summary
- Monthly Sales Trend
- Top 10 Products by Sales
- Sales by Category
- Sales by Region
- Discount vs Profit Analysis

Dashboard screenshots are available in the `Screenshots` folder.

---

## Business Recommendations

1. Focus on high-performing Technology products to maintain strong revenue and profitability.
2. Continue strengthening the West region while investigating opportunities in weaker regions.
3. Review loss-making products and evaluate pricing, costs, and discount strategies.
4. Control excessive discounts, especially for products with low profit margins.
5. Analyze high-sales but low-profit products before increasing their sales volume.
6. Use profitability-based decision making rather than focusing only on sales revenue.

---

## Project Structure

```text
FUTURE_DS_01/
│
├── Notebook/
│   └── Business_Sales_Performance_Analysis.ipynb
│
├── Tableau/
│   └── Business_Sales_Performance_Dashboard.twbx
│
├── Screenshots/
│   ├── dashboard_1.png
│   └── dashboard_2.png
│
└── Sample - Superstore.csv
