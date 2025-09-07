# Coffee Shop Sales – Excel Dashboard

A polished Excel dashboard that analyzes retail sales for a coffee shop chain and turns raw transaction data into actionable insights.

---

## 🎯 Objectives
- Analyze **sales by day of week** and **hour of day** to identify peak times.
- Compare **sales across store locations** (footfall & revenue).
- Calculate **average bill per person** and **average orders per person**.
- Identify **best-selling products** by **quantity** and **revenue**.
- Explore **sales by product category & size/type**.

---

## 📂 Repository Structure
coffee-shop-sales/
├─ excel/
│ └─ Coffee_Shop_Sales_Dashboard.xlsx # Main Excel model & dashboard
├─ data/
│ └─ transactions.csv # Raw or cleaned sales data (optional)
├─ docs/
│ └─ screenshots/
│ └─ coffee-dashboard.png # Exported dashboard image(s)
├─ README.md
└─ LICENSE


---

## 🔧 How to Use
1. Open `excel/Coffee_Shop_Sales_Dashboard.xlsx`.
2. On the **Data** sheet, update or refresh the source tables (Power Query or table links).
3. Review the **PivotTables** and press **Data → Refresh All**.
4. Explore the **Dashboard** sheet: slicers for **Month** and **Day**, charts for time-of-day and category breakdowns.

---

## 🧱 Data Model (Example)
- **transactions**: `order_id`, `datetime`, `day_name`, `hour`, `store_location`, `product`, `category`, `size`, `qty`, `unit_price`, `customer_id`
- Calculated fields inside Excel:
  - **Sales** = `qty * unit_price`
  - **Avg bill per person** = `Total Sales / Distinct Customers`
  - **Avg orders per person** = `Total Orders / Distinct Customers`

---

## 📊 Core Metrics & Visuals
- **KPI Cards**: Total Sales, Total Footfall (orders/customers), Avg Bill/Person, Avg Orders/Person
- **Line/Area**: Quantity ordered by **Hour** (peak times)
- **Bar**: Footfall & Sales by **Store Location**
- **Bar**: Top 5 Products by Sales
- **Pie/Donut**: Category % of Sales, Size % of Orders

---

## 🧠 Excel Skills Demonstrated
- Data preparation: **Remove Duplicates, TRIM, PROPER**, Text to Columns
- Lookups: **XLOOKUP / INDEX+MATCH**, **VLOOKUP**
- Aggregation: **SUMIF/SUMIFS**, **COUNTIFS**
- Time intelligence: **TEXT**, **WEEKDAY**, **HOUR**, custom date columns
- PivotTables, PivotCharts, **Slicers**
- Conditional Formatting & Chart formatting
- (Optional) **Power Query** for data import/cleaning

---

## 🚀 Reproduce / Refresh
1. Put your raw files in `data/` and update the query connections (if using Power Query).
2. Press **Data → Refresh All**.
3. Dashboard updates automatically.

---

## 📈 Business Insights (Examples)
- Peak order times are **morning 8–10 AM**, secondary peak around **5–7 PM**.
- **Lower Manhattan** and **Astoria** show highest sales & footfall.
- **Brewed Coffee** and **Barista Espresso** lead revenue; **Regular size** dominates order share.
- Average bill per person ≈ **$4–5**; average orders per person ≈ **1.4–1.5**.

---

## 📝 License
This project is released under the **MIT License**. See `LICENSE` file.

---

## 🙋 Contact
**Arbind Shah**  
LinkedIn: [www.linkedin.com/in/arbind-shah](https://www.linkedin.com/in/arbind-shah)
