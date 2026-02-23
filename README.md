# 💳 Credit Card Weekly Analysis Dashboard

## 📌 Project Overview

The **Credit Card Weekly Analysis Dashboard** was developed to provide financial stakeholders with structured, real-time insights into transaction performance and customer behavior.

The solution transforms raw transactional data into actionable intelligence through SQL-driven analytics and interactive BI reporting.

---

## 🎯 Project Objectives

- Identify spending trends and revenue drivers  
- Monitor interest income and transaction volumes  
- Detect anomalies and unusual behavioral patterns  
- Enable data-backed marketing and product decisions  

---

# 🏗️ End-to-End Methodology

---

## 1️⃣ Data Collection

### Data Sources
- Credit card transaction records  
- Customer demographic datasets  

### Key Fields Included
- Transaction Amount  
- Revenue  
- Interest Earned  
- Transaction Count  
- Customer Segment  
- Geographic Information (ZIP Code)  
- Gender-based segmentation  

---

## 2️⃣ Data Preparation & ETL

### 🗄️ Database Layer
- PostgreSQL used for structured storage and transformation  

### 🔄 ETL Process
- Data extraction via SQL queries  
- Cleaning inconsistent entries  
- Handling null values  
- Standardizing formats  
- Creating derived KPI tables  

The dataset was structured for performance-efficient reporting and scalable dashboard refresh.

---

## 3️⃣ Data Analysis Framework

### 📊 KPI Analysis

The following performance indicators were analyzed:

| KPI | Value |
|------|--------|
| Total Revenue | $55,315,410 |
| Total Interest Earned | $7,843,382 |
| Total Transaction Amount | $44,522,013 |
| Total Transaction Count | 655,651 |

---

### 📈 Segment Analysis

- Revenue contribution by customer demographics  
- ZIP code-based performance comparison  
- Gender-wise transaction behavior  
- High-performing vs underperforming segments  

---

### 🚨 Anomaly Detection

- Identified revenue spike on **May 21, 2023**
- Male customer revenue peaked at **$771,655**, exceeding normal variation thresholds  
- Triggered anomaly flag for further investigation  

---

### 📉 Trend Analysis

- Female customer revenue showed a **19.13% decline over 28 days**
- Observed cyclical transaction behavior across weeks
- Identified regional interest earning concentration (ZIP 91750 outperformed significantly)

---

# 📊 Dashboard Development

Two interactive dashboards were built using **Power BI**:

---

## 📌 1. Credit Card Transaction Report

Focused on:

- Revenue breakdown  
- Transaction volume trends  
- Interest income distribution  
- Segment-level performance  

---

## 📌 2. Credit Card Customer Report

Focused on:

- Customer behavioral patterns  
- Gender-wise revenue trends  
- Geographic analysis  
- Anomaly tracking  

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|-------|----------|
| PostgreSQL | Data storage & transformation |
| SQL | Querying & KPI extraction |
| Power BI | Interactive visualization & reporting |

---

# 🔍 Key Insights

### 💰 Revenue Insights
- Revenue concentrated within specific demographic and geographic clusters.
- Certain segments significantly outperformed average contribution rates.

### 📊 Interest Income Trends
- ZIP 91750 generated disproportionately high interest revenue.
- Interest distribution varied notably by customer segment.

### 👥 Customer Behavior
- Male customers showed higher short-term revenue volatility.
- Female revenue trend indicated sustained decline requiring strategy adjustment.

### 🚨 Risk & Monitoring
- Early anomaly detection supports proactive fraud or abnormal activity review.
- Transaction monitoring framework improves financial oversight.

---

# 💼 Business Impact

| Impact Area | Outcome |
|-------------|----------|
| Decision-Making | Data-driven revenue optimization |
| Risk Monitoring | Early anomaly detection capability |
| Marketing Strategy | Targeted demographic campaigns |
| Performance Tracking | Weekly KPI-based monitoring |

---

# 🏁 Conclusion

The Credit Card Weekly Analysis Dashboard demonstrates a structured analytics pipeline:

- Database-driven ETL (PostgreSQL)  
- KPI computation using SQL  
- Interactive business reporting (Power BI)  
- Trend and anomaly detection  

The project successfully converts transactional financial data into operational intelligence, enabling optimized revenue strategies, enhanced customer engagement, and improved monitoring within the financial services domain.

---

## 🔮 Future Enhancements

- Predictive customer churn modeling  
- Fraud risk scoring integration  
- Automated alert system for anomaly spikes  
- Real-time dashboard streaming  
