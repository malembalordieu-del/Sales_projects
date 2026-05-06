#  Strategic Profit & Growth Dashboard  
### Power BI Executive Analytics Project

---

##  Project Overview

This project transforms raw retail transactional data into a **Strategic Profit & Growth Intelligence Dashboard** using Power BI.

The objective is to move beyond basic reporting and deliver **executive-level insights** that clearly answer:

- What should we grow?
- What should we fix?
- What should we stop?

The dashboard connects operational performance (sales, profit, discounts, orders) to strategic business outcomes.

---

##  Business Problem

Retail executives often struggle to make informed strategic decisions because transactional data alone does not clearly reveal performance drivers.

While sales may increase, profitability does not always follow due to:

- Discount strategies  
- Product mix imbalance  
- Regional performance differences  
- Margin inefficiencies  

This dashboard was designed to bridge that gap.

---

##  Data Source & Structure

The dataset contains retail order-level transactional data from **2014–2017**.

Each row represents a **single product sold within an order**, enabling detailed profitability analysis at product, category, and regional levels.

### Key Fields Used

**Order Information**
- Order ID  
- Order Date  
- Ship Date  
- Ship Mode  

**Customer Attributes**
- Customer ID  
- Segment  

**Geography**
- Region  
- State  
- City  

**Product Information**
- Category  
- Sub-Category  
- Product Name  

**Financial Metrics**
- Sales  
- Quantity  
- Discount  
- Profit  

---

##  Dashboard Architecture

The Power BI report is structured into three strategic pages:

---

### 1️⃣ Executive Overview

Provides a high-level snapshot of business performance.

**KPIs Included**
- Total Sales  
- Total Profit  
- Profit Margin %  
- Total Orders  
- Sales YoY  
- Sales YoY %  

**Purpose:**  
Identify overall business health and growth trends.

---

### 2️⃣ Product Analysis

Focuses on product and category performance.

**Key Insights**
- Sales and profit by category  
- Sub-category contribution analysis  
- Product-level profitability  
- Margin performance evaluation  

**Purpose:**  
Determine which products and categories drive profit versus those that erode margin.

---

### 3️⃣ Regional Performance

Analyzes geographic performance differences.

**Key Insights**
- Sales and profit by region  
- Regional growth trends  
- Profitability comparison across regions  

**Purpose:**  
Identify high-performing regions and areas requiring optimization.

---

##  Key Findings

- The business generated **$2.30M in total sales** and **$286K in total profit**.
- Sales experienced strong year-over-year growth.
- Technology provides the strongest balance of revenue and profitability.
- Furniture generates high revenue but shows margin pressure.
- A small percentage of products drive a large portion of total profit.
- The West region leads in both sales and profitability.

---

##  Strategic Recommendations

###  Grow
- High-margin Technology products  
- Top profit-driving SKUs  
- Strong-performing regions (West & East)  
- Seasonal Q4 demand  

###  Fix
- Discount strategy in low-margin categories  
- Furniture margin optimization  
- Underperforming regional cost structure  

###  Stop / Reduce
- Consistently low-margin products  
- Excessive discounting practices  

---

##  Technical Implementation

The dashboard was developed using:

- Power BI Desktop  
- DAX measures for KPI calculations  
- Time intelligence functions (YoY analysis)  
- Interactive slicers (Year, Category, Region)  
- Conditional formatting to highlight growth and risk  

All visuals update dynamically based on user interaction.

---

##  Repository Contents

- `Profit&Growth_Project.pbix` – Interactive Power BI dashboard  
- `Profit&Growth_Project_Dashboard.pdf` – Dashboard export  
- `Profit&Growth_Project_Insights.pptx` – Executive presentation  
- `README.md` – Project documentation  

---

##  Conclusion

This project demonstrates how Power BI can be used not only for reporting but for **strategic business intelligence**.

By connecting sales performance, profitability, and growth trends, the dashboard enables leadership to make informed decisions on expansion, pricing strategy, and product portfolio optimization.
