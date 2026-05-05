# 🌐 Global Website Traffic Analysis 2026

## 📌 Project Overview
Analysis of **1,500 global websites** across 6 major markets 
to understand traffic patterns, user engagement, and market behavior.

---

## 🎯 Business Questions Answered
1. Which websites dominate global internet traffic?
2. Which category drives the most traffic?
3. Which market has the highest bounce rate?
4. Which category has the most engaged users?
5. How is traffic distributed across tiers?
6. Which websites keep users engaged the longest?

---

## 📊 Dataset
- **Source:** Kaggle — Global Website Traffic & Engagement Metrics 2026
- **Size:** 1,500 websites × 9 columns
- **Markets:** US, UK, Japan, Brazil, Germany, India
- **Columns:**
  - global_rank, domain, category, primary_market
  - monthly_visits, bounce_rate_pct, avg_session_duration_s
  - stickiness_index, last_crawled

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Python | Data cleaning, missing value treatment |
| Excel | EDA, Pivot Tables, Interactive Dashboard |
| Power BI | Final Interactive Dashboard |

---
## 📸 Dashboard Preview

### Excel Dashboard
![Excel Dashboard](Screenshots/Global%20Web%20Traffic%20Analysis-Excel%20Dashboard%20.png)

### Power BI Dashboard
![Power BI Dashboard](Screenshots/Global%20Web%20Traffic%20Analysis%202026%20-%20Power%20bi%20dashboard.png)

---

## 🔍 Key Findings
1. **Google.com** dominates with 997M monthly visits
2. **Social Media** category drives highest total traffic
3. **US market** has the best engagement scores
4. **Platinum tier** websites have lowest bounce rates
5. Dataset evenly distributed across 6 markets (~230-260 websites each)

---


## ⚙️ Data Cleaning Steps
1. Introduced realistic missing values (2-5% per column)
2. Filled numeric nulls with **median** (outlier resistant)
3. Filled categorical nulls with **mode**
4. Removed duplicates
5. Fixed data types
6. Created new features:
   - `avg_session_duration_min`
   - `engagement_score`
   - `traffic_tier` (Bronze/Silver/Gold/Platinum)

---

## 👤 Author
**Udhayanithi**
Aspiring Data Analyst
📧 nithiudhaya56@gmail.com
🔗 LinkedIn:www.linkedin.com/in/udhayanithi007
