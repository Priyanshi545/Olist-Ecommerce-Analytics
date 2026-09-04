# Olist E-Commerce Analytics Project

## Executive Summary
This project analyzes the Olist Brazilian e-commerce dataset to evaluate sales performance, customer behavior, delivery efficiency, product performance, and seller performance. Python was used for data preparation and exploratory analysis, while Power BI and DAX were used to build the final interactive five-page dashboard.

### Key Findings
- Total revenue: approximately **₹13.59M** (project reporting convention).
- Total orders: approximately **99.44K**.
- Unique customers: approximately **96.10K**.
- Total sellers: **3,095**.
- Total products: **32,951**.
- Average order value: approximately **₹136.68**.
- Delivered orders: approximately **96.48K**.
- Late orders: approximately **6.54K**.
- Late delivery rate: approximately **6.7%**.
- Repeat customers: approximately **2,997**, or about **3.1%** of unique customers.


## 1. Project Objective
Transform raw Olist e-commerce data into actionable business intelligence across executive performance, sales, customers, delivery, products, and sellers.

## 2. Business Questions
### Sales and Revenue
- How is revenue changing over time?
- Which states and product categories drive revenue?
- Does high order volume always translate into high revenue?

### Customer Analytics
- How many customers make repeat purchases?
- How does customer value vary by state?
- How does satisfaction vary with delivery performance?

### Delivery Analytics
- What proportion of orders are late?
- Which states have the highest late-delivery rates?
- Which states have the longest delivery times?

### Seller and Product Analytics
- Which sellers generate the most revenue?
- Which products and categories are strongest?
- Does seller order volume correspond to seller revenue?

## 3. Data Preparation and Methodology
**Workflow:** Raw Olist Dataset → Data Cleaning → EDA → Integrated Business Analysis → Power BI Data Model → DAX Measures → Interactive Dashboard.

Python tools included Pandas, NumPy, Matplotlib, and Seaborn. Power BI was used for dimensional modeling, relationships, DAX measures, KPI development, filtering, and dashboard design.

## 4. Data Model
Core dimensions include **DimCustomer, DimOrder, DimProduct, DimSeller, and DimDate**, supported by sales, payment, delivery, and customer-satisfaction analysis tables. Relationships were checked for grain, key uniqueness, cardinality, active status, and appropriate filter direction.

## 5. KPI Summary
| KPI | Result |
|---|---:|
| Total Revenue | ~₹13.59M |
| Total Orders | ~99.44K |
| Unique Customers | ~96.10K |
| Total Sellers | 3,095 |
| Total Products | 32,951 |
| Average Order Value | ~₹136.68 |
| Delivered Orders | ~96.48K |
| Late Orders | ~6.54K |
| Late Delivery Rate | ~6.7% |
| Repeat Customers | ~2,997 |
| Repeat Customer Rate | ~3.1% |

## 6. Page 1 — Executive Dashboard
The executive page provides high-level KPIs, revenue and order trends, revenue by state, delivery status, product-category performance, customer satisfaction, and key executive insights.

**Key insights:** SP is the dominant revenue market at approximately ₹5.20M; late delivery is approximately 6.7%; repeat customers are approximately 3.1%; revenue is concentrated in leading categories; and delivery performance is associated with customer satisfaction.

## 7. Page 2 — Sales & Revenue
This page analyzes monthly revenue, order volume, top product categories, revenue by state, and revenue versus order volume.

**Key insight:** SP is the largest revenue market, while high market volume does not necessarily imply the highest revenue per customer.

## 8. Page 3 — Customer Insights
This page analyzes customer volume, repeat purchasing, customer value by state, purchasing frequency, and satisfaction.

The analysis identified approximately **93,099 one-time customers** and **2,997 repeat customers**, producing a repeat-customer rate of approximately **3.1%**. Average orders per customer were approximately **1.00** for one-time customers versus **2.12** for repeat customers.

**Business implication:** customer retention is a major growth opportunity.

## 9. Page 4 — Delivery Performance
This page evaluates delivered orders, late orders, late-delivery rate, delivery time, state-level delays, delivery trends, and review scores by delivery status.

Approximately **6.7%** of delivered orders were classified as late. **AL recorded the highest late-delivery rate at approximately 20.58%** and average delivery time of approximately **23.99 days** in the project analysis. Other elevated-delay states included MA, SE, PI, CE, BA, and PB.

## 10. Page 5 — Seller & Product Performance
This page identifies top sellers, top products, category revenue contribution, seller revenue versus order volume, and multidimensional seller performance.

Seller performance should be evaluated using revenue, order volume, average order value, delivery time, and customer satisfaction together rather than revenue alone.

## 11. Key Business Insights
1. **Revenue concentration:** SP contributes approximately ₹5.20M.
2. **Retention opportunity:** only about 3.1% of customers are repeat purchasers.
3. **Delivery improvement:** overall late-delivery rate is approximately 6.7%, with substantial state-level variation.
4. **Customer value:** smaller states can generate higher revenue per customer than large-volume markets.
5. **Product concentration:** a limited number of categories contribute a meaningful share of revenue.
6. **Seller performance:** volume, value, delivery, and satisfaction should be considered together.

## 12. Business Recommendations
### Improve customer retention
Use personalized offers, post-purchase engagement, loyalty incentives, recommendations, and re-engagement campaigns.

### Prioritize high-delay states
Investigate logistics capacity, carrier performance, fulfillment processes, and estimated-delivery accuracy in high-delay states.

### Focus on high-value markets
Evaluate states with high revenue per customer for targeted expansion and acquisition.

### Strengthen category strategy
Monitor leading categories for assortment, availability, cross-selling, and targeted promotions.

### Monitor seller quality
Track seller revenue, orders, AOV, delivery time, and review score together.

## 13. Dashboard Pages
1. Executive Dashboard
2. Sales & Revenue
3. Customer Insights
4. Delivery Performance
5. Seller & Product Performance

## 14. Conclusion
The project demonstrates an end-to-end analytics workflow from Python data preparation and exploratory analysis to Power BI dimensional modeling, DAX, and interactive reporting. The major opportunities identified are customer retention, delivery improvement, high-value geographic expansion, category optimization, and multidimensional seller performance management.
