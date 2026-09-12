# 🛒 Olist E-Commerce Analytics

### Power BI | Python | Pandas | NumPy | DAX | Data Analytics

An end-to-end e-commerce analytics project using the **Olist dataset** to analyze sales performance, customer behavior, retention, delivery efficiency, product performance, seller performance, and customer satisfaction.

The project combines **Python-based data cleaning, exploratory analysis, and feature engineering** with **Power BI data modeling, DAX measures, and interactive dashboard development** to generate actionable business insights.

---

## 📈 Key KPIs

| KPI                      |   Result |
| ------------------------ | -------: |
| **Total Revenue**        | ~₹13.59M |
| **Total Orders**         |  ~99.44K |
| **Unique Customers**     |  ~96.10K |
| **Total Sellers**        |    3,095 |
| **Total Products**       |   32,951 |
| **Average Order Value**  | ~₹136.68 |
| **Delivered Orders**     |  ~96.48K |
| **Late Orders**          |   ~6.54K |
| **Late Delivery Rate**   |    ~6.7% |
| **Repeat Customers**     |   ~2,997 |
| **Repeat Customer Rate** |    ~3.1% |

---

## 🎯 Project Objective

The objective of this project is to analyze Olist e-commerce transactions and identify actionable insights across:

* Sales and revenue
* Customer behavior and retention
* Delivery performance
* Product categories
* Seller performance
* Geographic performance
* Customer satisfaction

The final output is an interactive **five-page Power BI dashboard** designed for executive reporting and business analysis.

---

# 📊 Dashboard Preview

## Executive Dashboard

![Executive Dashboard](Power_BI/Screenshots/Page_1.png)

## Sales & Revenue

![Sales & Revenue](Power_BI/Screenshots/Page_2.png)

## Customer Insights

![Customer Insights](Power_BI/Screenshots/Page_3.png)

## Delivery Performance

![Delivery Performance](Power_BI/Screenshots/Page_4.png)

## Seller & Product Performance

![Seller & Product Performance](Power_BI/Screenshots/Page_5.png)

---

# 📊 Power BI Dashboard

The Power BI dashboard consists of five analytical pages, with each page focused on a specific business area.

### Page 1 — Executive Dashboard

Provides a high-level view of overall business performance through:

* Revenue and order KPIs
* Customer metrics
* Average Order Value
* Delivery performance
* Product category performance
* Customer satisfaction

**Business purpose:** Provide an executive-level overview of the overall e-commerce business.

### Page 2 — Sales & Revenue

Analyzes sales performance through:

* Revenue trends
* Order volume
* Product categories
* Revenue by state
* Revenue vs. order volume

**Business purpose:** Identify major revenue drivers, geographic markets, and differences between sales volume and revenue contribution.

### Page 3 — Customer Insights

Analyzes customer behavior and value through:

* Customer distribution
* Repeat customers
* Customer value
* Orders per customer
* Customer satisfaction

**Business purpose:** Understand customer purchasing behavior and identify opportunities to improve customer retention and value.

### Page 4 — Delivery Performance

Analyzes logistics and delivery efficiency through:

* Delivery status
* Late delivery rate
* Average delivery time
* State-level delivery performance
* Delivery trends
* Customer satisfaction

**Business purpose:** Identify geographic delivery issues and areas where logistics performance can be improved.

### Page 5 — Seller & Product Performance

Analyzes seller and product contribution through:

* Top sellers
* Top products
* Product categories
* Seller revenue
* Seller order volume
* Seller performance

**Business purpose:** Compare seller and product contribution using multiple performance indicators rather than revenue alone.

---

# ❓ Business Questions

## Sales & Revenue

* How is revenue changing over time?
* Which states generate the highest revenue?
* Which product categories generate the most revenue?
* Does high order volume always translate into high revenue?

## Customer Analysis

* How many customers make repeat purchases?
* What is the repeat customer rate?
* Which states generate the highest revenue per customer?
* How does purchasing frequency differ between customer segments?

## Delivery Analysis

* What percentage of orders are delivered late?
* Which states have the highest late-delivery rates?
* Which states have the longest delivery times?
* Does delivery performance affect customer satisfaction?

## Seller & Product Analysis

* Which sellers generate the most revenue?
* Which products and categories contribute the most revenue?
* Does seller order volume correspond to seller revenue?
* Which sellers perform strongly across revenue, delivery, and customer satisfaction?

---

# 🛠️ Tools & Technologies

| Tool / Technology | Purpose                                     |
| ----------------- | ------------------------------------------- |
| **Python**        | Data cleaning, transformation, and analysis |
| **Pandas**        | Data manipulation and exploratory analysis  |
| **NumPy**         | Numerical analysis and calculations         |
| **Matplotlib**    | Data visualization                          |
| **Seaborn**       | Exploratory data visualization              |
| **Power BI**      | Interactive dashboard development           |
| **DAX**           | KPI calculations and analytical measures    |
| **Git & GitHub**  | Version control and portfolio management    |

---

# 🔍 Key Business Insights

### 1. Revenue Concentration

**São Paulo (SP)** is the largest revenue-generating state, contributing approximately **₹5.20M** in the project analysis.

This highlights the strong concentration of revenue within major geographic markets.

### 2. Customer Retention Opportunity

Only approximately **3.1% of customers are repeat customers**, indicating a significant opportunity to improve customer retention.

The analysis identified:

* **93,099** one-time customers
* **2,997** repeat customers

Repeat customers also place more orders per customer than one-time customers, highlighting the potential value of stronger retention strategies.

### 3. Delivery Performance

Approximately **6.7% of delivered orders were classified as late**.

**Alagoas (AL)** recorded the highest late-delivery rate at approximately **20.58%**, with an average delivery time of approximately **23.99 days**.

This identifies AL as an important region for logistics and delivery-performance improvement.

### 4. Customer Value

The analysis shows that customer volume does not necessarily translate into higher customer value.

Several smaller states generate higher revenue per customer than larger customer markets, demonstrating the importance of evaluating **revenue per customer alongside customer volume**.

### 5. Product Performance

Revenue is concentrated among leading product categories.

Category-level analysis can therefore support:

* Product assortment decisions
* Promotional planning
* Category prioritization
* Revenue-growth strategies

### 6. Seller Performance

Seller performance should not be evaluated using revenue alone.

A more complete assessment considers:

* Revenue
* Order volume
* Average Order Value
* Delivery performance
* Customer satisfaction

This provides a more balanced view of seller contribution and operational performance.

---

# 💡 Business Recommendations

Based on the analysis, the following business actions can be considered:

### 1. Improve Customer Retention

With only approximately **3.1% repeat customers**, Olist could focus on retention initiatives such as personalized offers, post-purchase engagement, and targeted promotions for existing customers.

### 2. Investigate High-Risk Delivery Regions

Regions such as **AL**, with significantly higher late-delivery rates, should be investigated for potential logistics, seller, transportation, or fulfillment issues.

### 3. Focus on High-Value Markets

Geographic markets with higher revenue per customer can be analyzed further to identify characteristics associated with higher customer value and replicate successful strategies where appropriate.

### 4. Optimize Product Categories

High-performing product categories can be prioritized for assortment planning and promotional campaigns while underperforming categories can be evaluated for improvement opportunities.

### 5. Evaluate Sellers Holistically

Seller evaluation should combine revenue, order volume, delivery performance, and customer satisfaction rather than relying on a single metric.

---

# 🧹 Data Analysis Workflow

```text
Raw Olist Dataset
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Business Analysis
        ↓
Data Integration
        ↓
Power BI Data Model
        ↓
DAX Measures
        ↓
Interactive Dashboard
        ↓
Business Insights
        ↓
Business Recommendations
```

---

# 📁 Repository Structure

```text
Olist-Ecommerce-Analytics/
│
├── data/
│   ├── Raw/
│   └── Processed/
│
├── notebooks/
│   └── Data analysis and transformation notebooks
│
├── Power_BI/
│   ├── Screenshots/
│   │   ├── Page_1.png
│   │   ├── Page_2.png
│   │   ├── Page_3.png
│   │   ├── Page_4.png
│   │   └── Page_5.png
│   │
│   └── Olist E-Commerce Dashboard.pbix
│
├── requirements.txt
├── .gitignore
└── README.md
```
---

# 📌 Project Highlights

This project demonstrates practical Data Analyst skills in:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data transformation
* Feature engineering
* Business-question-driven analysis
* KPI development
* Power BI data modeling
* DAX measure creation
* Interactive dashboard development
* Customer segmentation and retention analysis
* Delivery performance analysis
* Seller and product performance analysis
* Business insight generation
* Business recommendations
* GitHub portfolio development

---

# 📊 Project Outcome

The project transforms raw Olist e-commerce data into a structured analytical solution combining **Python, Pandas, Power BI, and DAX**.

The final dashboard provides a consolidated view of **sales, customers, products, sellers, delivery performance, geographic performance, and customer satisfaction**, helping identify key revenue drivers, retention opportunities, and operational improvement areas.

Overall, the project demonstrates an end-to-end **Data Analyst workflow — from raw data preparation to business-focused insights and interactive reporting**.
