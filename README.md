# 🛒 E-commerce Customer Analytics

## Overview

This project analyzes over **70,000 e-commerce transactions** to evaluate sales performance, customer behavior, and product returns. It combines SQL, Power BI, and DAX to build interactive dashboards and customer segmentation models that support data-driven business decisions.

The analysis provides actionable insights into customer purchasing patterns, sales trends, and business performance.

---

## Business Problem

E-commerce companies generate massive volumes of transactional data. However, transforming this data into actionable business insights remains a challenge.

This project aims to answer key business questions such as:

- Who are the most valuable customers?
- Which products generate the highest revenue?
- How do sales evolve over time?
- Which customers are at risk of churn?
- How can marketing campaigns be optimized?

---

## Dataset

The dataset contains more than **70,000 transactions**, including:

- Orders
- Customers
- Products
- Categories
- Payments
- Shipping
- Returns

---

## Technologies

- Power BI
- SQL
- DAX
- Python
- Excel

---

## Repository Structure

```text
ecommerce-customer-analytics
│
├── data
│
├── sql
│   ├── queries.sql
│   └── views.sql
│
├── dax
│   ├── measures.dax
│   └── calculated_columns.dax
│
├── powerbi
│   └── Ecommerce_Dashboard.pbix
│
├── dashboard
│   └── dashboard_preview.png
│
├── figures
│
├── README.md
└── requirements.txt
```

---

## Data Preparation

The workflow includes:

- Data cleaning
- Data transformation
- Missing value handling
- Feature engineering
- SQL querying
- Data modeling

---

## Key Performance Indicators (KPIs)

The dashboard monitors several business KPIs, including:

- Total Sales
- Total Orders
- Revenue
- Profit
- Average Order Value
- Number of Customers
- Customer Lifetime Value
- Return Rate
- Sales Growth

---

## Customer Segmentation

Customers were segmented into four groups:

- ⭐ VIP Customers
- ❤️ Loyal Customers
- 🛍️ Occasional Customers
- ⚠️ At-Risk Customers

This segmentation supports targeted marketing and customer retention strategies.

---

## RFM Analysis

Customer behavior was analyzed using the **RFM (Recency, Frequency, Monetary)** methodology.

### Metrics

- **Recency** – Days since last purchase
- **Frequency** – Number of purchases
- **Monetary** – Total amount spent

The RFM model helps identify high-value and inactive customers.

---

## Sales Analysis

The project includes analyses of:

- Monthly sales trends
- Revenue by category
- Top-selling products
- Regional performance
- Customer purchasing behavior
- Product returns
- Discount impact on sales

---

## Dashboard Features

The interactive Power BI dashboard allows users to:

- Track sales performance
- Monitor customer behavior
- Analyze product performance
- Explore regional sales
- Filter by category and time period
- Monitor business KPIs

---

## Project Outputs

- SQL scripts
- DAX measures
- Interactive Power BI dashboard
- Customer segmentation
- RFM analysis
- Sales performance reports
- Business insights

---

## Future Improvements

- Demand forecasting using Machine Learning
- Customer churn prediction
- Market basket analysis
- Recommendation system
- Interactive web dashboard using Streamlit

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ecommerce-customer-analytics.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Author

**Solagnon Edoh KOEVIDJIN**

**Data Scientist | Business Intelligence Analyst | Data Analytics**

---

## License

This project is licensed under the MIT License.
