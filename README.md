# Coffee Sales Analytics Project

A detailed data analytics project exploring customer behavior, product performance, and operational trends using transactional data from a coffee shop. Built with Python and visualized using Matplotlib and Seaborn, this project demonstrates how data storytelling can drive business decisions in retail and F&B environments.

---

## Dataset Overview

The dataset contains **1,133 transactions** from March to July 2024, with the following key fields:

- `date`: Transaction date
- `datetime`: Timestamp of purchase
- `hour`: Extracted hour from timestamp
- `day`: Day of the week (0 = Sunday, 6 = Saturday)
- `month`: Extracted month from date
- `cash_type`: Payment method (e.g., card)
- `card`: Anonymized customer ID
- `money`: Transaction amount
- `coffee_name`: Product purchased

---

## Objectives

- Identify top-selling coffee products and revenue contributors
- Analyze sales trends across hours, days, and months
- Understand customer purchase behavior and preferences
- Support inventory, staffing, and marketing decisions with data

---

## Key Analyses & Visualizations

### 1. **Revenue by Coffee Type**
- Grouped by `coffee_name`, summed `money`, and sorted descending
- Revealed **Latte** as the top revenue generator, **Espresso** as the lowest
- Bar chart with labeled revenue values

### 2. **Monthly Sales Trends**
- Pivoted monthly transaction counts by coffee type
- Line chart showed **Americano with Milk**, **Latte**, and **Cappuccino** as top performers
- Noted upward trends for **Latte** and **Americano with Milk**

### 3. **Weekday Sales Distribution**
- Grouped by `day` (0–6), counted transactions
- Bar chart revealed **Tuesday** as the highest sales day
- Other days showed relatively balanced activity

### 4. **Daily Product-Level Sales**
- Pivoted daily counts of each coffee type
- Summary stats showed **Americano with Milk** had the highest single-day sales (12 units)
- All products had days with zero sales—useful for restocking and promotions

### 5. **Hourly Sales Distribution**
- Grouped by `hour`, counted transactions
- Bar chart revealed **10 AM** as the peak hour (133 transactions)
- Secondary peaks at **12 PM** and **7 PM**

### 6. **Hourly Sales by Coffee Type**
- Pivoted hourly counts for each product
- Created 8-panel subplot showing time-of-day demand per coffee type
- Insights:
  - **Latte** and **Americano with Milk** peak at 10 AM and 7 PM
  - **Espresso** spikes mid-morning
  - **Cocoa** and **Hot Chocolate** trend in the evening

### 7. **Customer Purchase Analysis**
- Used anonymized `card` IDs to group purchases
- Aggregated:
  - Total spend per customer
  - Average spend
  - Number of transactions
  - Number of unique products tried
- Built preference matrix showing coffee types purchased per customer

### 8. **Daily Revenue Trend (All Customers)**
- Grouped by `date`, summed `money`
- Line chart revealed daily revenue fluctuations
- Useful for identifying high-performing days and seasonal patterns

---
## Tools & Technologies

- **Python**: Data manipulation and analysis
- **Pandas**: Grouping, pivoting, aggregation
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive analysis
- **Git/GitHub**: Version control and portfolio presentation

---

##  Insights Summary

- **Latte** and **Americano with Milk** are top sellers across timeframes
- **10 AM** is the busiest hour; **Tuesday** is the highest sales day
- Customer behavior shows repeat purchases and product loyalty
- Time-of-day analysis supports targeted promotions and staffing
- Daily and monthly trends reveal operational and marketing opportunities

---

##  Author

**Nisha Bisht**  
Early-career analyst with an MSc in Mathematics, passionate about data-driven decision-making, strategic storytelling, and impactful analytics.  
📍 Almora, Uttarakhand, India  
🔗 [LinkedIn](#) | [GitHub](#)

---
