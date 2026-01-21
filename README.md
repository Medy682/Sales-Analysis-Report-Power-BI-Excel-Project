 Sales-Analysis-Report-Power-BI-Excel-Project

Author: kidima Medy Masuka 

Date: 2026


✅ Project Overview
This project presents an end-to-end sales analysis using an Excel dataset and Power BI. The objective was to transform raw sales data into actionable business insights by applying proper data modelling, DAX time-intelligence, and business-focused KPIs. The final output is an interactive Power BI dashboard designed to support data-driven decision-making.

---

✅ End-to-End Analytics Workflow
- Excel → Power BI
- Raw data → meaningful insights
- Structured analysis aligned with real-world business questions

---

✅ Business Understanding

# Objective
Analyse sales performance to identify revenue trends, top-performing products, customer segments, and regional performance to support data-driven business decisions.

# Key Business Questions
- How are sales trending over time?
- Which products and subcategories drive the most revenue?
- Which regions and customer segments are most profitable?
- Where are sales underperforming or declining?

# Success Criteria
- Clear KPIs (sum of Sales, Sales Growth %, sum of Profit)
- Actionable insights for business stakeholders
- An interactive dashboard that supports exploration and decision-making

---

✅ Data Understanding

# Data Source
- Excel sales dataset containing orders, customers, products, regions, and dates

# Initial Exploration
- Reviewed columns, data types, and record counts
- Checked date ranges and missing values
- Identified categorical versus numerical fields

# Key Fields
- Date
- Sales
- Quantity
- Product Subcategory
- Customer Segment
- Region
- State

---

✅ Data Preparation

# Data Cleaning & Transformation (Power Query)
- Converted date columns to proper Date format
- Ensured data consistency and correctness

# Data Modelling
- Built a star schema:
  - Fact table: Orders
  - Dimension table: Date
- Created correct one-to-many relationships
- Optimised the data model for performance and scalability

---

✅ Modelling & Analysis

# Key DAX Measures Created
- sum of Sales
- Sales Last Year (Same Period Last Year)
- Sales Growth %
- Average Order Value
- Top N Products or top_performing products

# Analytical Focus
- Time-series analysis (monthly and yearly trends)
- Product and subcategory performance
- Regional sales distribution
- Customer segmentation insights

---

# Key Metrics & KPIs
- sum of Sales
- Sales Growth %
- Average Order Value
- Top-Performing Products
- Subcategory-level sales analysis

---

# Business Insight Highlight
Although **Phones** is the highest-selling subcategory overall, the top individual product is a **high-value copier (Canon imageCLASS 2200 Advanced Copier)**.  
This highlights the difference between:
- **High-volume product groups** (e.g. Phones), and
- **High-ticket individual items** (e.g. Copiers)

This distinction is important for understanding revenue drivers and informing pricing, inventory, and sales strategies.

---

✅ Evaluation & Validation

# Validation and Quality Checks
- Cross-checked Power BI results against Excel totals to ensure consistency
- Verified DAX calculations across different filters and time periods
- Ensured all visuals directly answered the stated business questions
- Tested slicers and filters for usability and correctness

# Key Findings
- Identified top revenue-generating product categories
- Discovered clear seasonal sales patterns
- Highlighted underperforming regions requiring business attention

---

# Tools Used
- Excel – data source and initial exploration
- Power Query – data cleaning and transformation
- Power BI – data modelling and visualisation
- DAX – KPI creation and time-intelligence calculations

---

# Deliverables
- Interactive Power BI dashboard
- Clean and validated data model
- Business-focused insights supported by accurate metrics


---
**Kidima Medy Masuka**  
Aspiring Data Scientist | Data Analyst  

Focused on data-driven decision-making, risk analytics, and machine learning


Usage & Attribution

This project is shared for educational and portfolio purposes.  
If reused or adapted, appropriate credit must be given to the author.

I would like to thank Mr Pavan Lalwani for sharing this Excel dataset and guiding us step by 
Step-by-step instructions on how to work with the Microsoft Business Intelligence software, Power BI

📰This project is part of my personal data science and analytics portfolio ✅


