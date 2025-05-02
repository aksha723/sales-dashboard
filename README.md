# 📊 Simple Sales Dashboard Project

## Dataset
**Source**: Superstore Sales Data  
**Columns Used**:
- ORDERNUMBER, ORDERDATE, PRODUCTLINE, SALES, COUNTRY, QTR_ID, YEAR_ID, STATUS

---

##  Objective
To build a simple and interactive dashboard using **Power BI** that visualizes:
- Sales performance over time (Month-Year)
- Sales distribution by Product Line
- Country-wise Sales contribution
- Region/category-wise filtering

---

## Tools Used
- Power BI (for dashboard design)
- Microsoft Excel (for data cleaning & formatting)

---

##  Data Preprocessing Steps
1. Cleaned unnecessary spaces and standardized column names
2. Converted `ORDERDATE` to `Month-Year` format
3. Created new calculated fields for better visualization:
   - `MonthYear = FORMAT(ORDERDATE, "MMM-YYYY")`

---

## 📊 Dashboard Visuals
1. **Line Chart** – Monthly Sales Trend (`MonthYear` vs `SALES`)
2. **Bar Chart** – Sales by Product Line (`PRODUCTLINE`)
3. **Donut Chart** – Sales by Country (`COUNTRY`)
4. **Slicer** – Region and Product Line filter for interactivity

---

##  Key Insights
1. **Classic Cars** was the highest-selling product line.
2. Sales peaked in **December 2004**.
3. **USA** contributed the most to sales in **Q2**.
4. Sales consistently grew between **2003 and 2005**.

---

##  Deliverables
-  Screenshot 
-  Insights.txt file containing 3–4 written observations
-  This README file for project documentation

---

##  Author
Aksha Teli  
Project for: *Dashboard Design Task / Assignment / Portfolio*
