# Supermarket Sales Analysis

## 📌 Project Description

This project uses **Python and Pandas** to clean, prepare, and analyze supermarket sales data.

The dataset used in this project is:

`SuperMarket.csv`

The goal is to clean the data and answer business questions using the available sales and transaction information.

---

## 🛠️ Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

* Checked data types
* Checked missing values
* Checked duplicate records
* Renamed columns
* Removed unnecessary columns
* Corrected data types
* Sorted the data
* Created 3 columns (Day, Month, Year)
* Created the `Satisfied` column based on the rating

**Satisfaction Rule:**

`Rating >= 7 → Satisfied`

`Rating < 7 → Not Satisfied`

---

## 📊 Business Analysis

### 1. Total Revenue

**Result:**

> **313,917.06**

---

### 2. Revenue by City

**Highest Revenue City:**

> **Naypyitaw — 107,795.81**

**Revenue by City:**

| City | Revenue |
|---|---:|
| Naypyitaw | 107,795.81 |
| Mandalay | 103,737.66 |
| Yangon | 102,383.59 |

---

### 3. Profit by Branch

**Most Profitable Branch:**

> **Giza — 5,198.51**

**Profit by Branch:**

| Branch | Profit |
|---|---:|
| Giza | 5,198.51 |
| Cairo | 5,012.69 |
| Alex | 4,933.65 |

---

### 4. Revenue and Profit by Product Category

**Top-Performing Category by Revenue:**

> **Food and beverages — Revenue: 55,020.60 | Profit: 2,643.74**

**Revenue and Profit by Category:**

| Product Category | Revenue | Profit |
|---|---:|---:|
| Food and beverages | 55,020.60 | 2,643.74 |
| Sports and travel | 53,320.63 | 2,566.57 |
| Fashion accessories | 53,198.48 | 2,583.10 |
| Electronic accessories | 52,651.89 | 2,520.12 |
| Home and lifestyle | 51,926.56 | 2,528.07 |
| Health and beauty | 47,798.90 | 2,303.24 |

---

### 5. Spending by Customer Type

**Customer Type That Spends More:**

> **Member — 180,645.08**

**Spending by Customer Type:**

| Customer Type | Spending |
|---|---:|
| Member | 180,645.08 |
| Normal | 133,271.99 |

---

### 6. Payment Method

**Most Popular Payment Method:**

> **Cash — 341 transactions**

**Transactions by Payment Method:**

| Payment Method | Transactions |
|---|---:|
| Cash | 341 |
| Ewallet | 338 |
| Credit Card | 309 |

---

### 7. Average Transaction Value

**Average Transaction Value:**

> **317.73**

---

### 8. Customer Satisfaction by Branch

**Branch with the Highest Satisfaction:**

> **Alex — 52.69%**

**Satisfaction by Branch:**

| Branch | Satisfaction |
|---|---:|
| Alex | 52.69% |
| Giza | 52.15% |
| Cairo | 46.04% |

---

### 9. Sales by Day and Month

**Highest Sales Day:**

> **Day 15 — 15,049.09**

**Highest Sales Month:**

> **Month 1 — 111,778.41**

---

### 10. Overall Customer Satisfaction

**Overall Satisfaction Percentage:**

> **50.30%**

---

## 📈 Visualizations

The analysis was visualized using **Matplotlib and Seaborn**, including:

* Revenue by city
* Profit by branch
* Revenue and profit by product category
* Spending by customer type
* Transactions by payment method
* Customer satisfaction by branch
* Revenue by month
* Overall customer satisfaction
