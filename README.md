# FUTURE_ML_01
## FUTURE_ML_01 — AI Powered Sales Forecasting Dashboard

It is implemented for the **Future Interns – Machine Learning Internship (Task 1)**.  
The goal is to use historical retail sales data to build an AI-based sales forecasting model and present insights using **Power BI**.

---

## PROJECT OBJECTIVE
The objective of this work is to:

- Analyze historical retail sales data  
- Identify sales trends and seasonal patterns  
- Build a Time-Series Forecasting Model using Prophet  
- Visualize Actual vs Forecasted Sales  
- Provide meaningful business insights & recommendations  

---

## Tools & Technologies Used
- Python (Google Colab)  
- Facebook Prophet – Time Series Forecasting  
- Pandas, Matplotlib  
- Power BI Desktop – Dashboard Visualization  

---

## Dataset Overview
The dataset represents historical retail store sales.

Important columns:
- **Order Date / ds** → Date of sale  
- **Sales / y** → Sales amount  

Prophet-generated columns:
- **yhat** → Predicted Sales  
- **yhat_lower** → Lower prediction limit  
- **yhat_upper** → Upper prediction limit  

Dataset Used:  
`Sample - Superstore.csv`

---

## Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Loaded dataset in Google Colab  
- Converted date column to datetime format  
- Prepared Prophet compatible data (`ds` & `y`)  
- Aggregated daily sales data  

### 2️⃣ Feature Engineering
- Generated monthly aggregated sales  
- Extracted seasonal components & annual trends  
- Checked holiday spikes  

### 3️⃣ Forecasting Model
- Built forecasting model using Facebook Prophet  
- Generated 30-day future forecast  
- Exported forecast results to CSV  
- Used forecast outputs in Power BI  

### 4️⃣ Power BI Dashboard
- Imported historical & forecasted data  
- Created interactive visuals showing:
  - Sales trends  
  - Seasonality  
  - Actual vs Predicted Sales  
  - Key metrics  

---

## Key Findings
- Strong seasonal patterns  
- Higher sales toward the end of the year  
- Lower sales in early months (especially February)  
- Overall positive upward trend in sales  

---

## Business Insights & Recommendations
- Stock inventory during peak demand periods  
- Run marketing campaigns during low-sales months  
- Use forecasted data for budgeting & planning  
- Data-driven decision making improves business accuracy  

---

## How to Use

### 🔹 Run the Forecast Script
1. Open the Python script in Colab / Jupyter  
2. Install Prophet:
pip install prophet
3. Run the script to generate forecast CSV  

---

## View Power BI Dashboard
1. Open `ML_TASK_1_BI_DASHBOARD.pbix`  
2. Refresh if necessary  
3. Explore the interactive dashboard  

---

## Conclusion
This project demonstrates how **Machine Learning + Business Intelligence** can help businesses predict future sales, understand trends, and make smarter decisions.
