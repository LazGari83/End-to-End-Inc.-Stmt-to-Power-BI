# 📊 Income Statement Dashboard (Python ETL + Power BI)

## 📌 Project Overview
This project demonstrates an **end-to-end workflow** that financial analysts and BI developers often build in real-world FP&A settings:
1. **Extract & Clean** raw sales data from Kaggle using Python (Pandas/SQL).
2. **Transform** the dataset into a P&L-ready fact table (Revenue, COGS, Gross Profit).
3. **Load & Visualize** in Power BI as an interactive Income Statement with YoY comparisons, KPIs, and trend analysis.

---

## 🛠️ Tools & Technologies
- **Python (Pandas, SQL)** in Kaggle Notebook  
- **Power BI Desktop** for data modeling & visualization  
- **GitHub** for project documentation & portfolio sharing  

---

## 🧹 ETL Process (Python in Kaggle)
- Normalized messy column names into consistent snake_case.  
- Converted data types (dates → datetime, revenue/cost → numeric).  
- Derived new fields:
  - `Profit = Revenue – Cost`
  - `Profit Margin = Profit / Revenue`
- Built a **fact table** (`fact_sales.csv`) for Power BI.  
- Created a **date dimension** for proper time intelligence.  

👉 Original Kaggle dataset: [Sales Data for Economic Data Analysis](https://www.kaggle.com/datasets/abhishekrp1517/sales-data-for-economic-data-analysis)  

---

## 📊 Power BI Dashboard
The Power BI report includes:

### 🔹 Income Statement Matrix
- Current vs Previous year  
- Dollar & % YoY Change  
- Highlighted Gross Profit
- KPI Cards

 <img width="1532" height="860" alt="image" src="https://github.com/user-attachments/assets/5bbe92c6-3f58-4856-8c1d-41a28605938d" />


---

### 🔹 Decompisition Tree
- Breakout of Gross Profit by category and Subcategories
- Breakout of Revenue by Country and States
- Year-over-Year % indicators with trend axis  

<img width="1539" height="869" alt="image" src="https://github.com/user-attachments/assets/54b08262-7669-4b79-a6ef-4f4b06f17110" />


---

### 🔹 Key Influencers
- Shows what factors are influencing Gross Profit Year over Year   

<img width="1529" height="866" alt="image" src="https://github.com/user-attachments/assets/198f4857-7ef1-4d14-b290-8a774c62ae20" />


---

### 🔹 Slicers & Interactivity
- Year / Quarter / Month  
- Category / Product / Region  
- Interactive filtering across all visuals  

---

## 🚀 How to Use
1. Clone or download this repository.  
2. Open **IncomeStatement.pbix** in Power BI Desktop.  
   - Data source = included `fact_sales.csv`  
3. Explore the **Income Statement dashboard**.  

---

## 🎯 Business Value
This report simulates what FP&A analysts deliver to stakeholders:
- Track financial performance at a glance.  
- Compare **current vs prior year** (YoY analysis).  
- Drill into categories, regions, or products.  
- Provide executives with **KPIs + visual storytelling**, not just numbers.  

---

## 📂 Repository Structure
