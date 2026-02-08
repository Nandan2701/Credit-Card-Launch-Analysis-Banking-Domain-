# 💳 Credit Card Launch Analysis (Banking Domain)

## 📌 Overview
This project analyzes customer spending behavior to support the launch of a new credit card for a legacy Indian bank.  
The objective is to identify high-value customer segments, optimal launch timing, key spending categories, and product features using historical transaction data.

The analysis was conducted using **SQL for data exploration and aggregation** and **Power BI for visualization and insight communication**.

---

## 🏦 Business Context
The bank plans to expand its product portfolio by introducing a new credit card. Before committing to a full-scale rollout, management requested a pilot analysis on a sample dataset to answer key strategic questions:

- Who are the most suitable customers for a credit card?
- Where and how do they spend?
- When is the right time to launch?
- Which features would drive adoption and repeat usage?

---

## 🎯 Objective
- Understand customer demographics and spending behavior  
- Measure income utilization to assess credit readiness  
- Identify high-impact spending categories  
- Recommend a focused launch and feature strategy based on data  

---

## 🗂️ Dataset Description
The dataset consists of **~4,000 customers across five Indian cities** and is structured into two tables:

### dim_customers
Contains customer-level attributes:
- Age group  
- Gender  
- Occupation  
- City  
- Monthly income  

### fact_spends
Contains transaction-level data:
- Spending category  
- Transaction amount  
- Transaction month  

Both tables are joined using a customer identifier to analyze spending behavior across demographic segments.

---

## 🛠️ Tools & Technologies
- **SQL** – Data cleaning, joins, aggregations, and metric calculations  
- **Power BI** – Interactive dashboards and insight visualization  

---

## 🔍 Analysis Approach

### 1. Data Preparation
- Joined customer and transaction tables
- Validated data consistency
- Created aggregated views by:
  - Age group
  - Occupation
  - City
  - Spending category
  - Month

### 2. Key Metrics
- Total and average spend by segment  
- **Income Utilization %**
Income Utilization = Avg Monthly Spend / Avg Monthly Income

- Category-wise spend distribution  
- Monthly transaction trends  
- City-level contribution to total spend  

---

## 📊 Key Insights

### Customer Segments
- **Age group 25–34** has the highest spending, followed by **35–45**
- Majority of high-spend customers in 25–34 are **salaried IT professionals**

### Spending Behavior
- Top spending categories:
- Bills
- Groceries
- Electronics
- Bills account for the largest share of recurring transactions

### Income Utilization
- Salaried IT professionals show higher income utilization
- Indicates higher likelihood of sustained credit card usage

### Timing
- Transactions peak in **September**, followed by **August**
- Suggests these months are optimal for a pilot or soft launch

### Geography
- **Mumbai, Delhi NCR, and Bangalore** contribute ~70% of total spending
- These cities represent the strongest initial markets

---

## 💡 Recommendations

Based on observed data patterns:

- **Target Segment**: Salaried IT professionals aged 25–34  
- **Launch Strategy**:
- Soft launch in Mumbai, Delhi NCR, and Bangalore
- Time launch around August–September
- **Card Features**:
- Incentives on bill payments
- Auto-pay functionality to retain users
- Higher credit limits for salaried professionals
- **UPI Consideration**:
- Enable RuPay cards for UPI linkage  
- Or offer rewards strong enough to compete with UPI for mid-size transactions  

---

## 📈 Dashboard
A Power BI dashboard was built to:
- Visualize spending patterns across demographics
- Track income utilization percentages
- Compare monthly and category-wise trends

The dashboard is designed for **business stakeholders**, focusing on clarity and decision support.

---

## 🧠 What This Project Demonstrates
- Practical SQL-based exploratory analysis  
- Translating raw data into business insights  
- Linking analysis outcomes to real product decisions  
- Clear communication of findings using dashboards  
