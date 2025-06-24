
# 📦 Inventory Management & Optimization Project  
**📁 Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
**📊 Focus Area:** Inventory Analysis | EOQ | ROP | ABC Classification | Vendor Lead Time  

---

## 🧠 Project Overview

This project analyzes the inventory data of a mid-sized manufacturing company producing alcohol and wine-based products. The company was facing challenges such as:
- Frequent **stockouts**
- **Excess inventory** leading to higher carrying costs
- **Procurement delays** due to vendor lead times

The goal was to uncover insights and suggest data-driven improvements for **optimal inventory management**.

---

## 📌 Key Objectives

✔️ Determine optimal inventory levels  
✔️ Identify fast/slow-moving items  
✔️ Analyze stockouts and overstock issues  
✔️ Streamline procurement & vendor performance  
✔️ Build an actionable inventory management strategy  

---

## 🔧 Data Used

The analysis was done using **six real-world inventory datasets**:
- `SalesFINAL.csv`: Product-level sales data
- `PurchasesFINAL.csv`: Purchase and vendor transactions
- `BegInvFINAL.csv`: Opening inventory
- `EndInvFINAL.csv`: Closing inventory
- `InvoicePurchases.csv`: Vendor invoices and freight details
- `2017 Purchase Price.csv`: Historical product pricing

---

## 📈 Techniques & Analysis Performed

### 🔠 ABC Classification
- Ranked products based on cumulative inventory value.
- A-category (top 70%) = 30.82% of value → requires highest control.

### 📦 EOQ & Reorder Point (ROP)
- EOQ calculated using annual demand, ordering cost (freight), and carrying cost.
- ROP based on lead time × daily demand to prevent stockouts.

### 🔁 Inventory Turnover & Days in Inventory
- Identified **top 10 fast- and slow-moving items** based on how long they stayed in stock.
- Fastest item cleared in **<2 days**, slowest took **~80+ days**.

### ⏱ Vendor Lead Time Analysis
- Measured `ReceivingDate - PODate` to find vendors with highest delays.
- Longest lead time: **~15.6 days** → procurement bottleneck identified.

---

## 📊 Key Visualizations

- Line chart of daily and weekly sales trends (by classification)
- ABC Category Distribution
- EOQ vs. Annual Demand line plot
- ROP Top 10 products
- Inventory Turnover vs. Carrying Cost
- Fast vs Slow-Moving Products subplot
- Vendor Lead Time bar chart

---

## 🧩 Business Insights & Recommendations

| Focus Area            | Insight                                                                 |
|-----------------------|-------------------------------------------------------------------------|
| Demand Forecasting    | Sales peak in January → increase orders before year-end                |
| Product Prioritization| A-category items = 30.82% value → prioritize for accuracy & control     |
| Reordering Strategy   | High ROP items need earlier restocking due to high demand + lead time  |
| Vendor Performance    | Some vendors caused 15+ day delays → leads to potential stockouts      |
| Inventory Efficiency  | Slow-movers inflate costs → consider promotions or reduced stocking    |

---

## ✅ Project Outcome

This project resulted in a complete inventory optimization strategy using real data. It delivered actionable KPIs, highlighted procurement bottlenecks, and recommended smarter inventory ordering and vendor management processes.
