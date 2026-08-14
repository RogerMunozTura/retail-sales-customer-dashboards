# Retail Sales & Customer Performance Dashboard

Interactive Tableau dashboard suite analyzing retail sales and customer performance, with dynamic year-over-year comparisons.

## Overview

This project delivers two linked, interactive Tableau dashboards — a **Sales Dashboard** and a **Customer Dashboard** — built to give business stakeholders a fast, filterable view of sales performance and customer behavior for a US-based retail business selling Furniture, Office Supplies, and Technology products.

## Business Problem

Stakeholders need a single place to track overall sales, profit, and quantity performance year-over-year, and to understand customer behavior — who the most valuable customers are and how purchase frequency is distributed — without digging through raw transactional data.

## Objectives

- Track headline KPIs (Total Sales, Total Profit, Total Quantity, Total Customers, Total Orders, Sales per Customer) with year-over-year comparison.
- Identify which product sub-categories drive sales and profit, and which are underperforming.
- Understand customer distribution by order frequency and identify top customers by profit.
- Allow drill-down by Category, Sub-Category, Region, and City.

## Dataset

I used the Sample Superstore dataset, a retail dataset covering US orders (2020–2023) across Furniture, Office Supplies, and Technology, split into Customers, Orders, Products, and Location tables.

## Tools & Technologies

- Tableau Desktop / Tableau Public

## Analysis

- Built a relational data model joining Orders, Customers, Products, and Location.
- Created calculated fields for KPIs and year-over-year comparisons, driven by a dynamic Year parameter.
- Designed two container-based dashboards with shared navigation and filters (Category, Sub-Category, Region, City).

## Key KPIs (2023)

**Sales Dashboard**
| KPI | Value | vs. PY |
|---|---|---|
| Total Sales | $733K | +20.4% |
| Total Profit | $93K | +12.5% |
| Total Quantity | 12K units | +26.8% |

**Customer Dashboard**
| KPI | Value | vs. PY |
|---|---|---|
| Total Customers | 693 | +8.6% |
| Total Orders | 1,687 | +28.3% |
| Sales per Customer | $1,058 | +10.8% |

## Dashboard

**Sales Dashboard**
![Sales Dashboard](images/sales_dashboard.png)

**Customer Dashboard**
![Customer Dashboard](images/customer_dashboard.png)

🔗 **Live on Tableau Public:** [Sales & Customer Dashboard](https://public.tableau.com/views/SalesCustomerDashboard_17866215257280/SalesDashboard)

## Repository Structure

```
retail-sales-customer-dashboards/
├── dashboard/
│   └── Sales & Customer Dashboards.twbx
├── data/
│   ├── Customers.csv
│   ├── Location.csv
│   ├── Orders.csv
│   └── Products.csv
├── images/
│   ├── sales_dashboard.png
│   ├── customer_dashboard.png
│   └── ...
├── LICENSE
└── README.md
```

## Author

**Roger Muñoz** — [LinkedIn](https://www.linkedin.com/in/roger-muñoz-259378375) · [GitHub](https://github.com/RogerMunozTura)
