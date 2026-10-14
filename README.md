<h1 align="center">🍔 Swiggy Sales Analysis Dashboard</h1>

<p align="center">
  An interactive Microsoft Excel dashboard that explores Swiggy sales trends and key performance indicators.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Food%20Delivery-FC8019?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Data%20Visualization-orange?style=for-the-badge" />
</p>

---

## 🎯 Project Overview

This project analyzes Swiggy food delivery sales data in a single, filter-driven Excel dashboard. Users can slice the data by month and food category to explore sales, ratings, and order behavior across time, cities, and states.

---

## 🖼️ Dashboard Preview

<p align="center">
  <img src="Swiggy%20Dashboard.jpg" alt="Swiggy Sales Dashboard" width="100%">
</p>

---

## 📈 Dashboard Features

- 🎛️ **Interactive slicers:** Months, Category
- 📅 **Monthly sales trend:** January to August
- 📆 **Daily sales trend:** Sales by day of the week
- 🗓️ **Weekly sales trend:** Week-by-week sales
- 🥗 **Food type split:** Veg vs Non-Veg
- 🏙️ **Top 5 cities:** Cities ranked by sales
- 🗺️ **State-wise map:** Sales by state
- 📊 **Quarterly table:** Sales, rating, and orders by quarter with color scales

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and dashboard building |
| Pivot Tables & Pivot Charts | Summarizing and visualizing data |
| Slicers | Interactive filtering |
| Filled Map Chart | State-wise sales view |
| Conditional Formatting | Color scales in the quarterly table |

---

## 🧹 Data Cleaning

- Removed **duplicate records** from the raw order data
- Handled **missing values** in key columns
- Standardized **text fields** (city, state, category) using `TRIM` and `PROPER`
- Verified data types for **date, rating, and amount** columns
- Created helper columns for **month, weekday, week number, and quarter**

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---|
| 💰 Total Sales | ₹53.01M |
| ⭐ Average Rating | 4.34 |
| 🧾 Average Order Value | ₹268.51 |
| 🗳️ Rating Count | 197.43K |
| 📦 Total Orders | ~197.5K |

---

## 🔍 Key Insights

**Overall**
- Total sales are **₹53.01M** with an average rating of **4.34**, so customer satisfaction is high.
- Quarterly ratings stay flat at about **4.3**, showing consistent service quality.

**Time Patterns**
- **Saturday is the strongest day (₹7.78M)** and **Tuesday is the weakest (₹7.36M)**. Weekend and Thursday sales stay high.
- Monthly sales **dip sharply in February** (about ₹6.3M) and recover to about **₹6.8M in May and August**.
- Weekly sales stay steady at about **₹1.5M** for most weeks. The first and last weeks are lower, likely because they are partial weeks.

**Quarterly**
- **Q1 (₹19.67M) and Q2 (₹19.90M)** are almost equal.
- **Q3 (₹13.44M) is lower** because the data only covers part of the quarter.

**Food Type**
- **Veg orders bring ₹34.38M (about 65%)** of sales, while Non-Veg brings **₹18.63M (about 35%)**.

**Cities & States**
- **Bengaluru is the top city at ₹5.5M**, far ahead of Lucknow (₹3.1M), Mumbai (₹3.0M), Hyderabad (₹3.0M), and New Delhi (₹2.8M).
- The map shows sales concentrated in southern and central states, with the highest state at about **₹5.5M**.

---

## 📂 Dataset

[⬇️ View Swiggy Raw Data (Google Drive)](https://drive.google.com/drive/folders/1LRBPgaVNf6tOttHjNvlGjsOsGh0qJOks?usp=sharing)

---

## 👩‍💻 Author

**Trupti Rani Mohapatro**

🔗 [LinkedIn](https://www.linkedin.com/in/trupti-rani-mohapatro-99545a36a/?isSelfProfile=true) | 💻 [GitHub](https://github.com/truptiranimohapatro)

⭐ If you found this project useful, consider giving it a star!
