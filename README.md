# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using Python, PostgreSQL, and Power BI to uncover spending patterns, customer segments, product preferences, and revenue trends. The analysis was performed on 3,900 customer purchase records to generate actionable business insights for improving marketing, loyalty strategies, and sales performance.

The project covers the complete data analytics workflow:

* Data loading and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* SQL-based business analysis
* Dashboard/report creation
* Business recommendations

---

# Project Objectives

* Understand customer purchasing behavior
* Identify high-value customer segments
* Analyze revenue trends across demographics
* Discover top-performing products and categories
* Evaluate discount dependency
* Generate business recommendations using data-driven insights

---

# Dataset Information

## Dataset Summary

| Metric          | Value |
| --------------- | ----- |
| Total Purchases | 3,900 |
| Total Columns   | 18    |
| Missing Ratings | 37    |

## Key Features

### Demographic Features

* Age
* Gender
* Location
* Subscription Status

### Purchase Features

* Item Purchased
* Category
* Purchase Amount
* Season
* Size
* Color

### Behavioral Features

* Discounts Applied
* Promo Codes
* Purchase Frequency
* Ratings
* Shipping Type

---

# Tools & Technologies Used

| Tool / Technology    | Purpose                         |
| -------------------- | ------------------------------- |
| Python               | Data analysis and preprocessing |
| Pandas               | Data manipulation               |
| NumPy                | Numerical operations            |
| Matplotlib / Seaborn | Data visualization              |
| PostgreSQL           | SQL querying and analysis       |
| Power BI             | Dashboard and reporting         |
| Jupyter Notebook     | Analysis environment            |
| Gamma                | PPT presentation creation       |

---

# Project Workflow

## 1. Data Loading

* Imported dataset into Python
* Explored dataset structure
* Verified data types and column names

## 2. Data Cleaning

* Handled missing values
* Standardized column names to `snake_case`
* Removed redundant columns
* Checked duplicates and inconsistencies

### Cleaning Highlights

* `promo_code_used` column was removed after confirming overlap with `discount_applied`
* Missing ratings were handled appropriately

---

# Exploratory Data Analysis (EDA)

EDA was performed to identify trends, patterns, and customer behavior insights.

## Analysis Performed

* Revenue analysis
* Customer segmentation
* Product performance analysis
* Shipping behavior analysis
* Discount dependency analysis
* Subscription behavior analysis
* Age-group revenue analysis

---

# Key Insights

## Revenue by Gender & Subscription

* Male customers generated higher total revenue
* Subscribers spent slightly more on average
* Subscribers contributed greater overall revenue

### Business Insight

Subscription-based customers are valuable and should be targeted with retention strategies.

---

## Shipping Type Analysis

* Express shipping users had the highest average spending
* Premium shipping customers represent high-value buyers

### Business Insight

Premium shipping users can be targeted for upselling and exclusive offers.

---

## High-Spending Discount Users

A strong segment of customers:

* Used discounts
* Still spent above the average purchase amount

### Business Insight

These customers are discount-responsive but remain high-value buyers, making them ideal for loyalty programs.

---

# Product Performance Analysis

## Top Rated Products

### Clothing

* Blouse
* Dress
* Jacket

### Footwear

* Sneakers
* Sandals
* Boots

### Accessories

* Handbag
* Belt
* Sunglasses

### Business Insight

Top-rated products should be highlighted in promotional campaigns and advertisements.

---

# Discount Dependency Analysis

## Key Findings

* Overall conversion rate: **80.56%**
* Some products heavily relied on discounts for purchases

### Most Discount-Dependent Products

* Coat
* Hoodie
* Sweater
* Jeans
* Boots

### Business Insight

Heavy discount dependency may reduce profit margins. Discount strategies should be reviewed carefully.

---

# Customer Segmentation & Loyalty

Customers were segmented based on purchase frequency:

| Segment   | Purchase Count |
| --------- | -------------- |
| New       | 1–2 Purchases  |
| Returning | 3–5 Purchases  |
| Loyal     | 5+ Purchases   |

## Key Findings

* Loyal customers were significantly more likely to hold active subscriptions
* Loyalty positively influenced subscription adoption

### Business Insight

Reward programs can help move customers from "Returning" to "Loyal" segments.

---

# Revenue by Age Group

| Age Group | Revenue Contribution |
| --------- | -------------------- |
| 18–25     | 38K                  |
| 26–35     | 72K                  |
| 36–45     | 68K                  |
| 46–55     | 54K                  |
| 56–65     | 32K                  |
| 65+       | 15.9K                |

## Key Insight

The **26–45 age group** generated the highest revenue.

### Business Recommendation

Marketing campaigns and loyalty investments should primarily target this age group.

---

# SQL Analysis

SQL queries were used in PostgreSQL for:

* Revenue calculations
* Customer segmentation
* Product ranking
* Discount analysis
* Aggregations and grouping
* Business KPI generation

## SQL Concepts Used

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* CASE Statements
* Aggregate Functions
* Window Functions
* Subqueries

---

# Power BI Dashboard

An interactive dashboard was developed in Power BI to visualize:

* Revenue trends
* Customer segments
* Product performance
* Subscription behavior
* Shipping insights
* Discount analysis

## Dashboard Features

* KPI Cards
* Interactive Filters
* Charts & Graphs
* Category-wise Analysis
* Revenue Breakdown
* Customer Insights

---

# Business Recommendations

## Boost Subscriptions

Promote exclusive subscriber benefits to increase recurring customers.

## Loyalty Programs

Reward repeat buyers and encourage movement into the loyal customer segment.

## Review Discount Policy

Reduce excessive discount dependency to protect profit margins.

## Targeted Marketing

Focus campaigns on:

* Ages 26–45
* Express-shipping customers

## Product Positioning

Highlight top-rated products in marketing campaigns and advertisements.

---

# Conclusion

This project demonstrates a complete end-to-end customer behavior analysis workflow using Python, SQL, and Power BI. The insights generated from the analysis help businesses better understand customer preferences, optimize marketing strategies, improve customer retention, and make data-driven business decisions.

---

# Author

**[Ashmita Karmakar]**
BCA Student | Aspiring Data Analyst
Python | SQL | Power BI | Data Analytics

