# 📊 Retail Executive Sales & Profitability Dashboard (Power BI)

## 📌 Project Summary
An interactive executive business intelligence dashboard designed in **Power BI** to monitor gross margin, regional profitability, order turnaround times, and product category health for an omnichannel retail business.

---

## 🛠️ Toolkit & Methods
- **Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Star Schema (1 Fact Table, 4 Dimension Tables)
- **Calculations:** Advanced DAX (Time Intelligence, Dynamic Measures, Profit Margins)
- **Data Prep:** Power Query (M Language) for ETL and data cleansing

---

## 🔍 Core Business KPIs Tracked
1. **Financial Health:** Total Sales, Gross Margin %, Operating Costs, and Year-over-Year (YoY) Growth.
2. **Category Performance:** Product matrix evaluating High-Revenue vs. Low-Margin items.
3. **Logistics & Delivery:** Average shipping days by transport mode and delivery delay rates.
4. **Geographic Breakdown:** Interactive maps showcasing sales distribution across regions.

---

## 📐 Key DAX Measures Formulated
- **Total Profit Margin %:**
  `Margin % = DIVIDE([Total Profit], [Total Revenue], 0)`
- **YoY Sales Growth:**
  `Sales YoY % = VAR PriorYear = CALCULATE([Total Revenue], SAMEPERIODLASTYEAR('Date'[Date])) RETURN DIVIDE([Total Revenue] - PriorYear, PriorYear, 0)`

---

## 💡 Executive Insights
- **Margin Optimization:** The Technology segment drove 45% of total revenue but had lower net margins due to heavy regional discounting.
- **Supply Chain Bottleneck:** Standard Class deliveries had a 12% delay during Q4 seasonal spikes, suggesting a need for carrier diversification.

---

## 👤 Author
**Sayed Inamulhasan**  
Aspiring Data Analyst  
GitHub: [Sayedinam](https://github.com/sayedinam)
