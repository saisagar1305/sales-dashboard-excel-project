# 🛒 Quick Commerce Analytics Dashboard

An end-to-end Excel analytics project analyzing **947,752 orders** across **8 quick commerce companies** and **12 Indian cities**.

---

## 📁 Project Structure

| File | Sheet(s) | Description |
|------|----------|-------------|
| `quick_commerce_Project.xlsx` | Quick_Commerce_Data | Raw dataset with 947,752 order records |
| `quick_commerce_Project.xlsx` | Pivot Tables | 10 pivot tables used for analysis |
| `quick_commerce_Project.xlsx` | Dashboard | Interactive Excel dashboard with charts & slicers |
| `quick_commerce_Project.xlsx` | Insights | 13 business insights with detailed answers |

---

## 📊 Dashboard Overview

### KPI Cards
| Metric | Value |
|--------|-------|
| Total Revenue | ₹541.08M |
| Total Orders | 947,752 |
| Average Customer Rating | 3.04 / 5 |
| Average Delivery Time | 16.51 minutes |

### Charts (6 Visualizations)
1. **Total Revenue by Company** — Bar chart comparing all 8 companies
2. **Order by City** — Horizontal bar chart across 12 cities
3. **Payment Method Usage** — Pie chart (COD, Credit Card, UPI, Debit Card, Wallet)
4. **Average Delivery Time by Company** — Horizontal bar chart
5. **Order by Age Group** — Bar chart (Adults, Middle Age, Seniors, Young Adults)
6. **Product Category Revenue** — Donut chart (Beverages, Dairy, Groceries, etc.)

### Interactive Slicers
`Company` | `Age Group` | `Payment Method` | `Product Category` | `City`

---

## 🔢 Pivot Tables (10 Total)

| # | Pivot Table |
|---|-------------|
| 1 | Total Revenue by Company |
| 2 | Order by City |
| 3 | Product Category Revenue |
| 4 | Payment Method Usage |
| 5 | Average Delivery Time by Company |
| 6 | Average Customer Rating by Company |
| 7 | Order by Age Group |
| 8 | Discount Impact Analysis |
| 9 | Revenue by Product Category and City |
| 10 | Delivery Partner Rating Analysis |

---

## 💡 Key Insights (From Actual Data)

| Area | Finding |
|------|---------|
| 🏆 Top Revenue Company | **Swiggy Instamart** — ₹76.41M |
| 🚀 Fastest Delivery | **Zepto** — 9.64 mins avg (only company under 10 mins) |
| 🐢 Slowest Delivery | **Jio Mart** — 23.01 mins avg |
| ⭐ Best Customer Rating | **Blinkit** — 3.58/5 |
| ⚠️ Worst Customer Rating | **Dunzo** — 2.43/5 |
| 👥 Most Active Age Group | **Seniors** — 314,724 orders (33.2% of all orders) |
| 💳 Payment Distribution | All 5 methods nearly equal; digital payments = 79.9% |
| 🌆 City Distribution | Perfectly balanced — all 12 cities within 905 orders of each other |
| 🏷️ Discount Impact | Discounted orders have 49.5% higher avg order value (₹712 vs ₹476) |
| 📦 Top Product Category | **Dairy** — ₹78.06M (all 7 categories within ₹1.3M of each other) |

> Full insights with detailed analysis are in the **Insights sheet**

---

## 🗂️ Dataset Columns

| Column | Description |
|--------|-------------|
| `Order_ID` | Unique order identifier |
| `Company` | Quick commerce platform (8 companies) |
| `City` | Delivery city (12 cities) |
| `Customer_Age` | Age of the customer |
| `Age_Group` | Young Adults / Adults / Middle Age / Seniors |
| `Order_Value` | Order value in INR |
| `Delivery_Time_Min` | Delivery time in minutes |
| `Distance_Km` | Delivery distance in kilometers |
| `Items_Count` | Number of items in the order |
| `Product_Category` | Category of products ordered (7 categories) |
| `Payment_Method` | Mode of payment used (5 methods) |
| `Customer_Rating` | Customer rating (1–5 scale) |
| `Discount_Applied` | Whether a discount was applied (0 = No, 1 = Yes) |
| `Delivery_Partner_Rating` | Delivery partner performance rating |

---

## 📈 Company Performance Summary

| Company | Revenue | Avg Delivery | Avg Rating |
|---------|---------|-------------|------------|
| Swiggy Instamart | ₹76.41M | 16.07 mins | 3.28 |
| Blinkit | ₹72.50M | 15.12 mins | 3.58 ⭐ |
| Zepto | ₹70.34M | 9.64 mins 🚀 | 3.20 |
| Big Basket | ₹67.88M | 18.03 mins | 3.10 |
| Flipkart Minutes | ₹67.00M | 17.05 mins | 3.02 |
| Amazon Now | ₹65.83M | 18.98 mins | 2.91 |
| Dunzo | ₹64.01M | 14.18 mins | 2.43 ⚠️ |
| Jio Mart | ₹57.11M | 23.01 mins ⚠️ | 2.82 |

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Slicers, Charts, Dashboard Design, Conditional Formatting
- **Data Analysis** — Aggregations, Grouping, Trend Analysis, Discount Impact Analysis

---

## 🏙️ Cities Covered

`Amritsar` | `Bengluru` | `Chennai` | `Delhi` | `Gurgaon` | `Haridwar` | `Hyderabad` | `Jaipur` | `Kolkata` | `Mumbai` | `Noida` | `Pune`

---

## 🏪 Companies Analyzed

`Amazon Now` | `Big Basket` | `Blinkit` | `Dunzo` | `Flipkart Minutes` | `Jio Mart` | `Swiggy Instamart` | `Zepto`


