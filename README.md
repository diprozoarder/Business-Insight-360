# 📊 Business Insights 360 – End-to-End Power BI Solution for AtliQ Hardware

## 🚀 Project Overview

AtliQ Hardware, a global consumer electronics company, faced significant challenges using traditional Excel-based reporting systems. In particular, a costly decision in the Latin American market exposed their lack of data-driven decision-making capability. In response, the leadership initiated a company-wide data analytics transformation.

**Business Insights 360** is the first cross-functional Power BI dashboard rolled out to empower stakeholders from **Finance, Sales, Marketing, Supply Chain, and Executive leadership** with real-time analytics. The solution ensures streamlined insights for proactive decision-making and future growth.

🔗 **Live Dashboard**: **[Click Here](https://project.novypro.com/SS0LOS)**
   **Presentation Video**: **[Click Here](https://www.linkedin.com/posts/a-m-mohaiminur-zoarder-9a675512a_powerbi-businessintelligence-dataanalytics-activity-7359453392013811712-cdQ8?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAB_KcE4BAHNXmq8jZGCRmY8ilHNOKpwq928)** 

🧠 Built as part of Codebasics' Data Analytics Bootcamp – [Course Link](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance)


---

## ⚙️ Tech Stack

- SQL (MySQL Database)
- Power BI Desktop
- Power Query
- DAX
- Excel

---

## 🎯 Business Goals

- Provide **data-backed insights** across departments
- Enable **C-Level decision-makers** with clear and concise visuals
- Improve forecasting, cost efficiency, and profitability
- Replace manual Excel reporting with **automated dashboards**

---

## 📘 Key Concepts & Power BI Techniques Learned

- Data modeling using **Snowflake schema**
- Creating **calculated columns and measures** using DAX
- Dynamic field parameters and slicers
- Drill-down & tooltips
- Page navigation and bookmarks
- KPI visualization with dynamic thresholds
- Handling zero-division errors with `DIVIDE()`
- Creating custom **date tables** using M language
- Conditional formatting with icons & background color
- Publishing reports to **Power BI Service**
- Setting up **data refresh** via Personal Gateway
- Designing and managing **Power BI apps** and workspaces
- Data validation and performance optimization with **DAX Studio**

---

## 🧠 Business Terminology Covered

- Gross Sales / Net Sales
- Pre and Post Invoice Deductions
- Gross Margin / Net Profit
- COGS (Cost of Goods Sold)
- Forecast Accuracy (FCA%)
- Net Error
- YTD / YTG / LY comparisons
- Market Share, RC%, Segment & Sub-zone analysis
- Risk categorization (Excess Inventory / Out of Stock)

---

## 🏢 Company Background

**AtliQ Hardware** is a global B2B electronics company with operations spanning multiple continents. They sell via three key channels:

- 🛒 Retailers
- 🧑‍💼 Direct B2B Sales
- 📦 Distributors

After expanding to Latin America and facing loss due to inadequate forecasting and outdated analytics, they initiated a company-wide BI transformation initiative.

---

## 💡 Questions Asked Before Starting the Project

- What is the primary objective of this dashboard?
- What metrics matter most to each stakeholder group?
- What’s the expected ROI or impact of the solution?
- How will the dashboard be used in day-to-day decision-making?
- What are the fears, hopes, and expectations from each department?
- What timelines and milestones are required?
- What are the design preferences or restrictions from stakeholders?

---

## 📊 Dataset Overview

The project uses a **real-world dataset** (anonymized & modified) stored in a **MySQL data warehouse**. Below is the schema structure:

### Schema: `gdb041` (Transactional + Dimension)
- `dim_customer` – 75 customers across 27 markets; channels: Retailer, Direct, Distributor
- `dim_product` – Categorized into Divisions (P&A, PC, N&S), 14+ product categories
- `dim_market` – Organized by Region, Market, Sub-zone
- `fact_sales_monthly` – Actual sales performance
- `fact_forecast_monthly` – Forecasted sales quantity for proactive planning

### Schema: `gdb056` (Costing & Pricing)
- `gross_price`, `manufacturing_cost`, `freight_cost`
- `pre_invoice_deductions`, `post_invoice_deductions`

---

## 📐 Data Modeling Approach

Used the **Snowflake Schema** to normalize dimensions and optimize performance.

> Poor modeling → Slow dashboards.  
> Great modeling → Fast insights. ⚡


---

## 🧾 Dashboard Sections

### 🔹 **Home Page**
- Button-based navigation to all report pages
- Acts as a centralized index

![Demo GIF](https://github.com/user-attachments/assets/cfb6f957-db7d-46c9-a0a2-be121e9e46e5)




### 🔹 **Finance View**
- Interactive P&L table (Gross Sales → Net Profit)
- Dynamic YoY performance chart
- KPI Cards (Net Sales, GM%, NP%)
- Top/Bottom products & customers (switchable via field parameters)

![FINANCE VIEW](https://github.com/user-attachments/assets/13ac449c-ebac-4803-9ad3-7999695bb2c0)


### 🔹 **Sales View**
- Net Sales vs GM% Scatter Plot (Customer/Region toggle)
- Matrix table with dynamic Product vs Customer comparison
- Donut charts (Pre/Post invoice deduction & COGS breakdown)

![SALES VIEW](https://github.com/user-attachments/assets/74d7e452-43c0-495f-a83e-13e570c1e82e)


### 🔹 **Marketing View**
- Dynamic Scatter Chart (NP% / GM% by Division)
- Donut and Waterfall for margin & expense visualization
- Matrix of Net Sales, GM%, NP%, growth metrics by multiple hierarchies

![MARKETING VIEW](https://github.com/user-attachments/assets/2be8408b-050a-4df3-9b84-ffb62e8754e7)


### 🔹 **Supply Chain View**
- KPIs: FCA%, Net Error, Absolute Error
- Clustered chart for FCA trend analysis
- Product & customer level forecast performance
- Inventory Risk identification (Out of Stock / Excess)

![SUPPLY CHAIN VIEW](https://github.com/user-attachments/assets/104db278-3f3d-4059-a89d-b99079a47651)


### 🔹 **Executive View**
- Summary KPIs (NS, GM%, NP%, FCA%)
- Ribbon Chart for market share (AtliQ: 5.87% in 2022)
- Top 5 customers/products by RC% & GM%
- Performance over time: NS$, GM%, NP%, Market Share%
- Division & Channel revenue breakdown

![EXECUTIVE VIEW](https://github.com/user-attachments/assets/19742861-6693-44e5-960d-e83892ecc35b)

---



## 💥 Project Outcome

✅ Enhanced decision-making using real-time insights  
✅ Improved profitability & cost control  
✅ Greater visibility into forecast errors and supply chain risk  
✅ Replaced Excel dependency with scalable Power BI solution

---

## 📁 Data Model

![Data Model](https://github.com/user-attachments/assets/b0df1647-5eb7-49bc-9f48-7c21285df734)



---


## 🌐 Connect with Me

Let’s collaborate or discuss data analytics opportunities!

🔗 [LinkedIn](https://www.linkedin.com/in/a-m-mohaiminur-zoarder-9a675512a/)  
📬 [Email](diprozoarder@gmail.com)  


---

## 📈 Keywords for Discoverability

`Power BI Project` `Power BI Dashboard` `Business Intelligence` `Data Analytics` `SQL and Power BI` `Real-World Power BI` `Finance Analytics` `Sales Dashboard` `Marketing BI` `Supply Chain Insights` `Executive KPI` `Forecast Accuracy` `Market Share Analysis` `Field Parameters in Power BI` `DAX Measures`

---

