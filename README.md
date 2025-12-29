**🌌 Galaxy E-commerce: Strategic Sales & Operations Dashboard**
**📌 Project Overview**
This project provides a comprehensive, data-driven analysis of the **Galaxy E-commerce Store**. The dashboard transforms complex raw transactional data into actionable insights, enabling stakeholders to monitor revenue health, evaluate **shipping performance**, and identify **high-value customer segments**.

**📊 Key Performance Indicators (KPIs)**
**Total Revenue & Profit:** A high-level view of the store's bottom line.

**Profit Margin %:** Tracking profitability across various product lines.

**Order Volume:** Total quantity of items sold to monitor market demand.

**Average Order Value (AOV):** Insights into customer spending behavior.

**Shipping Efficiency:** Measuring the gap between order date and delivery date.

**🛠️ Technical Highlights**
**1. Data Engineering (Power Query)**
**ETL Process:** Performed extensive data cleaning, including handling missing values and standardizing regional data formats.

**Data Transformation:** Created custom columns for **Shipping Duration** and **Profit Segments**.

**2. Data Modeling**
**Schema Design:** Implemented a robust **Star Schema** with a central **Fact Table** (Sales) connected to multiple **Dimension** Tables (Product, Date, Geography, and Customer).

**Optimization:** Optimized the model for fast cross-filtering and high-speed report performance.

**3. Advanced DAX Calculations**
**Time Intelligence:** Created measures for **Year-over-Year (YoY) Sales** and **Month-to-Date (MTD) Profitability**.

**Dynamic Visuals:** Used DAX to create **Top 5 Product Rankings** and **Conditional Formatting** logic for target vs. actual performance.

**📈 Business Insights & Impact**
**Regional Dominance:** Identified the **West Region** as the primary revenue driver, while the **South Region** showed the highest profit growth potential.

**Category Performance:** Discovered that Technology leads in revenue, but **Office Supplies** has a higher retention rate and lower return frequency.

**Logistics Bottleneck:** Pinpointed a 12% delay in shipping for **Standard Class** orders in specific metropolitan areas, recommending a localized warehouse strategy.

**📂 Project Structure**
**Galaxy E-commerce Store Dashboard.pbix —** **The Core Power BI File** (Interactive Dashboard).

**Data/ —** Folder containing the cleaned dataset (CSV format).

**Visuals/ —** Folder with high-resolution Dashboard Screenshots for quick preview.

**🚀 How to Interact with the Dashboard**
**Clone** this repository to your local machine.

Open the **.pbix** file using **Power BI Desktop**.

Use the **Region**, **Year**, and **Category** slicers on the left pane to drill down into specific data points.
