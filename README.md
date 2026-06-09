# Global Electronics Retailer Analysis

## Dashboard Gallery

### Executive Overview

![Executive Overview](dashboard_images/executive_overview.png)

### Product Performance Analysis

![Product Performance Analysis](dashboard_images/product_performance.png)

### Customer Insights Analysis

![Customer Insights Analysis](dashboard_images/customer_insights.png)

---

# Project Overview

This project analyzes a Global Electronics Retailer dataset using Python (Pandas) and Tableau. The objective was to understand overall business performance, identify revenue-driving products and brands, and analyze customer demographics and spending behavior through interactive dashboards.

The project follows a complete analytics workflow beginning with exploratory data analysis, followed by KPI design, dashboard development, business insight generation, and interactive reporting.

---

# Business Questions

The analysis was built around three key business questions:

1. How is the company performing overall?
2. Which products and brands drive business performance?
3. Who are our customers and which customer segments generate revenue?

---

# Tools Used

* Python
* Pandas
* Tableau
* Git
* GitHub

---

# Data Exploration & Preparation

Before building the dashboards, exploratory data analysis was performed using Pandas to understand the dataset structure and quality.

### Checks Performed

* Dataset shape and structure
* Data type validation
* Missing value analysis
* Duplicate record analysis
* Unique value analysis
* Relationship validation between tables

### Data Preparation

* Created Revenue and Cost metrics
* Calculated Profit Margin %
* Created Age field
* Created Age Group segmentation
* Created Revenue per Customer metric
* Validated KPI calculations used in dashboards
* Identified and excluded non-country values such as "Online" from geographic analysis where appropriate

---

# Dashboard 1: Executive Overview

## Objective

Provide a high-level snapshot of overall business performance and enable quick business decision-making.

## KPIs

* Revenue
* Profit
* Profit Margin %
* Orders

## Visualizations

* Revenue Trend
* Revenue by Category
* Revenue by Country Map

## Design Rationale

Revenue by Category was retained instead of both Revenue and Profit by Category because both charts showed a very similar ranking pattern. To avoid redundancy and maximize dashboard space, the dashboard focuses on Revenue by Category while using other visualizations to provide additional business perspectives.

## Key Insights

* Computers generated the highest revenue.
* The United States generated the highest revenue.
* Business maintained strong profitability with a profit margin above 50%.
* Revenue trends provided a quick view of business growth over time.

---

# Dashboard 2: Product Performance Analysis

## Objective

Identify top-performing brands and profitable product categories.

## KPIs

* Revenue
* Profit
* Profit Margin %
* Quantity Sold

## Visualizations

* Top Brands by Revenue
* Profit Margin by Category
* Revenue vs Profit by Brand

## Design Rationale

Revenue vs Profit by Brand was included to understand whether high-revenue brands also generate proportionally high profits and to identify brands that may drive revenue but underperform in profitability.

## Key Insights

* Adventure Works was the highest revenue-generating brand.
* Contoso ranked as the second highest revenue-generating brand.
* Music, Movies and Audio Books delivered the highest profit margin.
* Games and Toys recorded the lowest profit margin.
* Desktops emerged as the strongest revenue-generating subcategory during exploration.

---

# Dashboard 3: Customer Insights Analysis

## Objective

Understand customer demographics and spending behavior.

## KPIs

* Total Customers
* Total Orders
* Revenue per Customer
* Average Customer Age

## Visualizations

* Revenue per Customer by Age Group
* Revenue by Gender
* Customer Count by Country

## Design Rationale

Revenue per Customer by Age Group was retained instead of Revenue by Age Group because it provides deeper insight into customer value. This helps identify which customer segments spend the most on average rather than simply identifying segments with the highest revenue volume.

## Key Insights

* Customers aged 65+ contributed significantly to revenue.
* Revenue per customer varies across age groups.
* The United States has the largest customer base.
* Revenue contribution is relatively balanced across genders.

---

# Design Choices

* A consistent blue color palette was used across all dashboards.
* Limited colors were intentionally used to keep the focus on insights rather than visual decoration.
* KPI cards were placed at the top of every dashboard for quick access to key business metrics.
* Borders and containers were used to improve readability and visual separation.
* Consistent typography, spacing, and layout structure were maintained across all views.
* Filters were synchronized across related worksheets to improve interactivity and user experience.

---

# Overall Business Insights

* Computers emerged as the primary revenue-driving category.
* Adventure Works was the leading revenue-generating brand.
* Music, Movies and Audio Books achieved the highest profit margin.
* The United States generated the highest revenue and maintained the largest customer base.
* Customers aged 65+ represented a high-value customer segment.
* Revenue and profitability were strongly aligned for leading brands.

---

# Project Learnings

* Improved Tableau dashboard design and layout planning.
* Practiced KPI selection based on business objectives.
* Applied exploratory data analysis before visualization development.
* Learned to translate business questions into interactive dashboards.
* Improved business storytelling through data visualization.
* Gained experience designing multi-view executive dashboards.

---

# Repository Structure

```text
global-electronics-retailer-analysis/
│
├── dashboard_images/
│   ├── executive_overview.png
│   ├── product_performance.png
│   └── customer_insights.png
│
├── documentation/
│   └── Documentation.pdf
│
├── notebooks/
│   └── EDA.ipynb
│
├── tableau/
│   └── Global_Electronics_Retailer_Final.twbx
│
└── README.md
```

---

# Author

**Madan Andahiphale**

Aspiring Data Analyst | Data Science Enthusiast

LinkedIn: [www.linkedin.com/in/madandahiphale](http://www.linkedin.com/in/madandahiphale)
