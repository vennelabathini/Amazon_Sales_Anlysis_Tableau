# Amazon_Sales_Anlysis_Tableau

#Tableau · Retail / E-Commerce Analytics

An interactive Tableau dashboard analyzing Amazon sales in India across product categories, sizes, sales channels, fulfillment status, and states. Every chart and KPI is driven by a single Category filter, so users can slice the entire report to reveal where revenue and demand concentrate and how effectively orders are being fulfilled — supporting decisions in sales strategy, inventory, and logistics.

📊  Key Visualizations


KPI Header Cards. Six calculated-field metrics — currency (INR), total quantity (116,649 units), total revenue (₹78.59M), total sizes (11), total categories (9), and total products (7,190, counted via distinct ASIN).
Quantity by Week & Category (Stacked Bar). Weekly units sold, segmented by category, to spot peak periods and underperforming lines.
Amount by Week & Category (Line / Area). Weekly revenue trend with color-coded categories for financial comparison over time.
Quantity by Size & Category (Bar). Sales broken down by product size, guiding stocking strategy (mid-range M/L/XL lead demand).
Top 10 States by Ship-Service Level (Horizontal Bar). Ranked states split by Expedited vs. Standard shipping to read regional and logistics performance.
Quantity by State (Map). A geographic view of demand across India for regional marketing and inventory placement.
Courier Status (Donut). Fulfillment health at a glance — 94.21% shipped, 5.79% unshipped, ~0% cancelled.
Sales Channel & B2B (Highlight Tables). Amazon.in 99.86% vs. non-Amazon 0.14%, and a 0.72% B2B share — exposing channel concentration.



<img width="624" height="354" alt="Picture10" src="https://github.com/user-attachments/assets/3a472fd5-3cb7-4870-9695-ded6ff355418" />


🧱 How It Was Built


Data import & prep: Loaded the Amazon Sale Report file (128,000+ rows) and focused on key fields — order ID, category, size, date, status, fulfillment, SKU, ASIN, courier/query status, quantity, amount, and the B2B flag.
Calculated fields: Built measures for currency, total quantity, total amount, total sizes, total categories, and total products (a distinct count of ASIN).
Visualization: Created each chart — stacked bar, line/area, bar, horizontal bar, map, donut, and highlight tables — with sorting, filtering, and percentage calculations.
Assembly: Combined all sheets into one layout, wired the Category filter across every view, and applied a consistent dark theme with logos, colors, borders, and aligned text.


🎯 Project Purpose

The dashboard gives sales, marketing, and logistics teams a single interactive view of where demand and revenue concentrate, how fulfillment is performing, and which channels and regions warrant attention.

👥 Stakeholders


Sales Teams: Forecast demand and allocate resources by region and category.
Marketing Teams: Target high-demand states with localized campaigns.
Logistics Managers: Monitor fulfillment and shipping-service performance.
Business Analysts: Track trends and channel mix for strategy decisions.


🏆 Achievements and Metrics


Confirmed healthy fulfillment — 94.21% of orders shipped with negligible cancellations.
Flagged extreme channel concentration (99.86% Amazon.in, <1% B2B) as a diversification opportunity.
Located demand in Maharashtra, Karnataka, and Tamil Nadu, guiding inventory and logistics placement.


🚀 How to Use

Open the .twbx in Tableau (Desktop or Public) and use the Category filter and interactive elements to explore demand, revenue, fulfillment, channels, and regions. Hover any element for detailed values.

🛠️ Tools Used

Tableau — stacked/horizontal bar charts, line and area charts, geographic map, donut chart, highlight tables, calculated fields, KPI cards, an interactive category filter, and a custom dark theme.

✅ Conclusion

A practical retail-analytics dashboard that translates 128,000+ rows of raw e-commerce data into clear, actionable insight for sales and operations teams.
