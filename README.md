# 📊 E-commerce Sales Analysis

## 📌 Objective

Analyze sales data to identify revenue trends, profitability issues, and business opportunities.

---

## 🗂️ Dataset

The dataset contains transactional sales data from an e-commerce business, including:

* Orders and shipping details
* Customer information
* Product categories and sub-categories
* Sales, profit, and discount data

---

## 🧰 Tools Used

* SQL (Google BigQuery)
* Excel (data cleaning and preparation)
* Tableau

---

## 🔍 Analysis Performed

### 1. Data Cleaning

* Corrected date formats
* Created new variables:

  * Year
  * Month (YYYY-MM)
  * Profit margin (profit / sales)

---

### 2. Exploratory Data Analysis

* Sales range: 2014–2017
* Identified seasonal trends (higher sales in November and year-end period)

---

### 3. SQL Analysis

Key business questions answered:

* Which categories generate the most revenue?
* Which categories and sub-categories are profitable?
* Are there loss-making segments?
* How do discounts impact profitability?

---

## 💡 Key Insights

### 📉 Loss-Making Sub-Categories

* Tables
* Bookcases
* Supplies

---

### 🟥 Tables (Critical Issue)

* Negative profit margin
* High variability in profit
* Losses not fully explained by discounts

👉 Indicates potential pricing or cost structure problems

---

### 🟧 Bookcases (Inconsistent Performance)

* Slightly positive average margin
* Overall negative profit
* High variability

👉 Suggests inconsistent pricing or discount strategy

---

### 🟨 Supplies (Outlier-Driven Losses)

* Positive average margin
* Negative total profit

👉 Losses likely driven by extreme negative transactions

---

### 💸 Discounts vs Profitability

* Higher discounts generally reduce profitability
* However, some products remain profitable even with high discounts

👉 Discounts alone do not explain losses

---

## 📊 Business Recommendations

* Review pricing strategy for Tables
* Investigate cost structure of low-performing products
* Optimize discount policies
* Identify and manage extreme loss-making transactions
* Focus on high-performing seasonal periods (e.g., November)


## 📊 Dashboard

👉 Images

