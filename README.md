# beverage-sales-inventory-optimization
🥈 Hackathon-winning Power BI dashboard providing data-driven insights to optimize sales, pricing, and inventory for a beverage distributor.
# 🥈 Optimizing Beverage Sales & Inventory Management | Hackathon Winner

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-FF6B00?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)

## 🏆 Achievement
**2nd Place Winner** in the [Name of Hackathon] hosted by [Organization Name].

## 📖 Project Overview
This project was a data-driven case study for a leading beverage distributor facing challenges in:
- Understanding regional customer preferences.
- Optimizing inventory to reduce overstocking and stockouts.
- Analyzing pricing strategies to maximize revenue.
- Identifying seasonal sales trends.

The goal was to analyze their sales data and provide actionable, data-backed recommendations to improve operational efficiency and profitability.

## 📊 Data Description
The dataset contained over [Number] rows of sales records with the following key attributes:
- **Sales:** `Sale (Dollars)`, `Bottles Sold`, `Volume Sold (Liters)`
- **Product:** `Item Description`, `Category Name`, `Bottle Volume (ml)`
- **Store & Location:** `Store Name`, `City`, `County`, `Store Location`
- **Financials:** `State Bottle Cost`, `State Bottle Retail`

*Note: The original dataset is not included in this repository due to its proprietary nature.*

## 🛠️ Tools & Technologies Used
- **Microsoft Power BI:** For primary data modeling, DAX measures, and interactive dashboard creation.
- **Microsoft Excel:** For initial data exploration, cleaning, and pivot table analysis.
- **DAX (Data Analysis Expressions):** To create calculated columns and measures for KPIs.
- **Data Visualization:** Designed intuitive and impactful charts for stakeholder reporting.

## 📈 Key Performance Indicators (KPIs) & Measures
I developed the following core DAX measures to drive the analysis:

| KPI | DAX Measure Purpose |
| :--- | :--- |
| **Total Sales** | Calculate total revenue. |
| **Total Profit** | `SUMX(Sales, (Retail - Cost) * Quantity)` |
| **Profit Margin** | `(Total Profit / Total Sales)` |
| **Inventory Turnover** | `SUM(Bottles Sold) / AVERAGE(Inventory)` |
| **Stockout Rate** | Percentage of items with zero stock. |
| **MoM Sales Growth** | Month-over-Month sales percentage change. |

## 🔍 Main Insights & Recommendations
### 1. Sales Performance
- **Insight:** The top 5 products contributed to over 30% of total revenue. Carbonated drinks dominated sales, but health-conscious beverages showed a 15% YoY growth.
- **Recommendation:** Focus marketing budgets on high-growth categories like functional health drinks in urban areas.

### 2. Inventory Management
- **Insight:** 20% of products were consistently overstocked, tying up capital, while 8% faced frequent stockouts during peak summer months.
- **Recommendation:** Implement a dynamic inventory system with reorder points based on historical seasonal demand.

### 3. Pricing Strategy
- **Insight:** Products in the `Craft Soda` category showed low price elasticity, meaning a 5% price increase did not significantly affect demand.
- **Recommendation:** Apply a strategic price increase on low-elasticity items to boost profit margins without losing sales.

### 4. Regional Trends
- **Insight:** Sales of premium beverages were 40% higher in urban store locations compared to rural ones.
- **Recommendation:** Develop region-specific product assortments and promotions.

## 📸 Dashboard Preview
![Power BI Dashboard Screenshot](PowerBI_Dashboard/Dashboard_Screenshot.png)
*The interactive dashboard provided a holistic view of sales, inventory, and profitability across regions and product categories.*

## 🚀 How to Explore This Project
1. **View the Presentation:** The `Presentation/` folder contains the final PowerPoint deck presented to judges.
2. **Explore the Dashboard:** Download the `.pbix` file from the `PowerBI_Dashboard/` folder and open it in Power BI Desktop (free to download).
3. **See the Analysis:** The `Excel_Analysis/` folder contains the supporting Excel workbooks.

## 💡 Lessons Learned
- Translating vague business problems into specific, measurable KPIs is crucial.
- Clean, well-modeled data is the foundation of any insightful dashboard.
- The most effective data stories are those that lead to clear, actionable business recommendations.

## 👨‍💻 Author
**Your Name**
- [LinkedIn](https://www.linkedin.com/in/yourprofile/)
- [Portfolio](https://yourwebsite.com/)

---
**⭐ Feel free to star this repo if you found it helpful!**
