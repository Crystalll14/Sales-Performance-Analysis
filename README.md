# 🛍️ Superstore Sales Performance Analysis

An end-to-end sales performance analysis project built using the Superstore Sales dataset.  
This project focuses on transforming raw transactional data into business-ready insights through data modeling, DAX calculations, and dashboard design in Excel.


## 📌 Project Objective

The objective of this project is to evaluate overall business performance, identify revenue drivers, measure year-over-year growth, and detect geographic concentration risks.

The goal is not just to build visuals, but to answer real business questions using structured data modeling and analytical thinking.


## ❓ Key Business Questions (KPIs)

The analysis was guided by the following business questions:

- What are our **Total Revenue, Orders, Quantity Sold, and Average Discount**?
- How are these metrics performing **Year-over-Year (YoY)**?
- Which states and regions generate the highest revenue?
- How concentrated is revenue among the top-performing states?
- Which customer segments drive the most value?
- Which product categories contribute most to overall sales?
- Are we overly dependent on a small number of markets?

### Core KPIs Built

- Total Revenue  
- Total Orders  
- Total Quantity  
- Average Discount  
- Revenue YoY  
- Orders YoY  
- Quantity YoY  
- Discount YoY  


## ⚙️ Process

### 1️⃣ Data Preparation

- Reviewed dataset structure (Sales, Orders, Customer, Region, Category, Dates)  
- Cleaned inconsistencies  
- Created a proper Calendar table for time intelligence  
- Loaded data into the Excel Data Model  

### 2️⃣ Data Modeling

- Built a structured star-schema model  
- Created relationships between fact and dimension tables  
- Ensured correct filter context for accurate DAX calculations  

### 3️⃣ DAX Calculations

- Developed base measures (`SUM`, `COUNTROWS`, `AVERAGE`)  
- Implemented dynamic Year-over-Year KPIs using:
  - `VAR`
  - `CALCULATE`
  - `ALL`
  - `DIVIDE`

Handled edge cases:

- No prior year data  
- Multiple year selections  
- Division-by-zero scenarios  

Built a Location Summary measure to:

- Rank top 5 states by revenue  
- Calculate revenue concentration %  
- Compare top state vs average state  
- Identify strongest and weakest regions  

### 4️⃣ Wireframing & Dashboard Design

- Defined layout hierarchy before styling  
- Positioned executive KPIs at the top  
- Ensured clear visual flow  
- Applied consistent performance indicators (▲ ▼ ▶)  
- Prioritized clarity and usability over decoration  


## 📊 Project Insights

- Revenue is highly concentrated in a small number of states.  
- The top 5 states account for a significant share of total revenue.  
- The leading state significantly outperforms the average state.  
- One region dominates overall performance, while another lags.  
- Consumer segment contributes the highest revenue.  
- Category contribution is uneven across product groups.  

Overall, the business shows strong performance but carries geographic concentration risk.


## 🏁 Final Conclusion

The Superstore business demonstrates solid revenue generation and growth trends. However, dependency on a limited number of high-performing states increases strategic risk.

### Recommendations

- Expand focus into underperforming regions  
- Diversify revenue across mid-tier markets  
- Monitor discount strategy to protect margins  
- Continue tracking YoY trends for sustainable growth  


## 🛠️ Tools Used

- Microsoft Excel  
- Excel Data Model  
- DAX (Data Analysis Expressions)  
- Pivot Tables & Dashboard Design  


## 📎 Resources

- 📂 [Download Dataset](./Superstore_Sales_Data.xlsx)
- 📊 [View Dashboard](./DashboardImage.png)

Superstore Sales Dataset (Sample retail transactional dataset commonly used for BI practice projects)

<img width="1270" height="730" alt="image" src="https://github.com/user-attachments/assets/43a8afc7-50d6-4340-a78e-6d178023061c" />
