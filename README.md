# Tableau Sales & Customer Dashboard

Two linked Tableau dashboards built on retail sales data, with year-over-year comparisons.

## Overview

I built two dashboards that talk to each other — a Sales Dashboard and a Customer Dashboard — for a retail business selling Furniture, Office Supplies, and Technology. The idea was to give someone a fast, filterable view of how the business is doing and who its customers actually are, without needing to touch the raw data.

This exercise, and the approach behind it, comes from Data With Baraa's Tableau course, where he walks through exactly this kind of dashboard-building process.

## The problem

If you want to know how sales are trending or who your best customers are, you shouldn't have to dig through transaction-level data every time. I wanted one place that answers both questions, with the ability to filter down by category, region, or city.

## What I tried to do

- Track the headline numbers (sales, profit, quantity, customers, orders) with a year-over-year comparison built in.
- Show which product sub-categories are actually driving sales and profit, and which aren't.
- Understand customer behavior — how often people buy, and who the most valuable customers are.
- Let someone drill down by Category, Sub-Category, Region, and City.

## Dataset

The Sample Superstore dataset — US retail orders from 2020–2023 across Furniture, Office Supplies, and Technology, split into Customers, Orders, Products, and Location tables. It's a well-known practice dataset.

## Tools

- Tableau Desktop / Tableau Public

## How I built it

- Joined Orders, Customers, Products, and Location into one data model.
- Built calculated fields for the KPIs and the year-over-year comparisons, driven by a Year parameter.
- Laid out both dashboards with containers, shared navigation, and the same set of filters.

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
