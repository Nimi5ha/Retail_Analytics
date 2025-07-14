#🛍️ Retail Sales Analytics Dashboard

Power BI, Python (Pandas, Seaborn, Matplotlib) | Customer & Revenue Insights | Dec 2010 – Dec 2011

📌 Objective

To uncover revenue opportunities and customer behavior patterns using retail transaction data from an online store. The project combines Python-based analytics and Power BI dashboarding to enable data-driven decisions on sales, customer retention, and anomalies.


---

📊 Dashboard Highlights

Built an interactive Power BI dashboard analyzing 9.52M+ in revenue across 406K+ customers from 38+ countries. Delivered insights on:

📌 Top-performing products & countries

👥 Customer segmentation using RFM

📈 Monthly sales trends

🕒 Hourly purchase behavior

🌍 Geographic performance


> 🔗 The dashboard includes filters for Time, Year, Country, and Customer Segment, enabling deep slice-and-dice analysis.




---

🔍 Key Insights

1. Customer Segmentation (RFM Analysis)

Segmented customers into 4 actionable groups based on Recency, Frequency, and Monetary metrics:

Segment	Count	Description

Champions	1660+	Frequent, high-spending recent buyers
Potential	950+	New or high-value customers to target more
Loyal	850+	Consistent repeat buyers
At Risk	800+	Inactive customers needing reactivation


> 📌 This segmentation enabled tailored marketing and loyalty strategies.




---

2. Anomaly Detection

Detected unusual spikes in daily sales using Top 1% transaction threshold:

Highest spikes on:

📅 2011-01-18 → $168,465

📅 2011-12-09 → $333,516


High-value orders (top 1%) included invoices over $100K+


> 🧠 These anomalies help identify bulk purchases, seasonal spikes, or fraud potential.




---

3. Cohort Analysis

Analyzed retention behavior of monthly customer cohorts:

Initial retention drops sharply after Month 1

Strongest retention in Dec 2010 cohort (up to 6 months)

Most cohorts drop below 20% retention after 3 months




> 📈 This analysis highlights the need for stronger post-purchase engagement campaigns.




---

📌 Tools & Techniques Used

Area	Tools / Methods

Data Cleaning	Pandas, Power Query
Customer Segments	RFM Segmentation using Quantiles
Anomaly Detection	Top 1% Thresholding, Daily Sales Patterns
Retention Analysis	Cohort Heatmaps with Seaborn
Visualization	Power BI (KPIs, Line Graphs, Maps, Matrix)



---

🧠 Business Impact

Helped stakeholders understand who the most valuable customers are

Identified drop-off points in customer lifecycle

Revealed seasonal buying patterns and sales spikes

Built interactive tools for filtering insights by region, time, and behavior



---

📁 Folder Structure

Retail_Analytics_Project/
│
├── data/
│   ├── OnlineRetail.csv
│   └── Retail_Analytics_CleanData.csv
│
├── notebooks/
│   └── Retail_Analysis.ipynb
│
├── dashboard/
│   └── Retail_Sales_PowerBI.pbix
│
├── images/
│   ├── cohort_heatmap.png
│   ├── anomaly_spike_chart.png
│   └── dashboard_screenshot.png
│
└── README.md

