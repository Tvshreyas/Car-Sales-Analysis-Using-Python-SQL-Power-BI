# 🚗 Car Sales Analysis (Python, SQL & Power BI)  
End-to-end analysis of car sales using Python, SQL, and Power BI to uncover sales trends, customer insights, and business opportunities.  
Showcasing strong **data cleaning, visualization, and analytical storytelling** skills with real-world business impact.  

---

## 📌 Table of Contents  
- [Overview](#-overview)  
- [Business Problem](#-business-problem)  
- [Dataset](#-dataset)  
- [Tools & Technologies](#-tools--technologies)  
- [Project Structure](#-project-structure)  
- [Data Cleaning & Preparation](#-data-cleaning--preparation)  
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  
- [Research Questions & Key Findings](#-research-questions--key-findings)  
- [Dashboard](#-dashboard)  
- [How to Run This Project](#-how-to-run-this-project)  
- [Final Recommendations](#-final-recommendations)  
- [Author & Contact](#-author--contact)  

---

## 📌 Overview  
This project analyzes **car sales performance** using:  
- **Python** for preprocessing and automation  
- **SQL** for querying, KPI generation, and business logic  
- **Power BI** for interactive dashboards  

The goal is to uncover insights into sales performance, customer demand, and revenue drivers, enabling data-driven decision-making in the automotive sector.  

---

## 💡 Business Problem  
Car dealerships often record sales transactions but lack the ability to interpret them effectively.  
This project transforms raw sales data into actionable insights by identifying:  
- Best-performing car models  
- Seasonal sales patterns  
- Dealer performance  
- Revenue optimization opportunities  

---

## 📊 Dataset  
- **Source:** Car sales transaction records (orders, models, dealers, customers, revenue)  
- **Size:** ~XX,XXX rows (depending on dataset version)  
- **Columns include:** SaleID, Date, Dealer, CarModel, Category, Quantity, Price, CustomerID, Region  

---

## 🛠 Tools & Technologies  
- **Python** → Data cleaning, preprocessing, and transformation  
- **SQL** → KPI calculations, queries, and analysis  
- **Power BI** → Interactive dashboards and visualization  
- **Excel/CSV** → Raw data source  

---

## 📂 Project Structure  
📁 Car-Sales-Analysis-Using-Python-SQL-Power-BI
│
├── data/
│ ├── raw/ # Original CSV/Excel files
│ ├── cleaned/ # Processed datasets after cleaning
│ └── sample_data.csv # Example dataset
│
├── sql/
│ ├── Car_Sales_Cleaning.sql # Queries for cleaning raw data
│ ├── Car_Sales_KPIs.sql # KPI calculations & aggregations
│ └── Car_Sales_Insights.sql # Analytical queries for findings
│
├── python_scripts/
│ ├── data_cleaning.py # Script to clean and preprocess data
│ ├── eda_visualization.py # Python visualizations (matplotlib/seaborn)
│ └── export_to_sql.py # Export cleaned data into SQL tables
│
├── powerbi/
│ ├── car_sales_analysis.pbix # Power BI dashboard
│ └── images/ # Dashboard screenshots
│
├── notebooks/
│ └── Car_Sales_Analysis.ipynb # Jupyter Notebook with full workflow
│
├── README.md # Project documentation
└── requirements.txt # Python dependencies
---

## 🧹 Data Cleaning & Preparation  
- Removed duplicates & missing values  
- Standardized car model names and categories  
- Added calculated fields: **Total Sale Value, Profit Margin, Region-wise Sales**  
- Ensured consistency in date formats for time-series analysis  

---

## 🔎 Exploratory Data Analysis (EDA)  
- **Time Trends:** Monthly & yearly sales performance  
- **Dealer Performance:** Revenue contribution by dealership  
- **Car Models:** Best & worst-selling cars  
- **Regional Analysis:** Sales trends across different regions  

---

## ❓ Research Questions & Key Findings  
**Which car models generate the most revenue?**  
→ SUVs and Premium models contributed the highest revenue.  

**Which dealers perform best?**  
→ Dealer X and Dealer Y accounted for 40% of total sales.  

**When are sales highest?**  
→ Seasonal peaks during **festive seasons and year-end promotions**.  

**What is the average sales value per transaction?**  
→ Approximately **₹XX,XXX per transaction**.  

---

## 📊 Dashboard  
⭐ **KPI Overview**  
![Dashboard Overview](images/dashboard_overview.png)  

📅 **Sales Trends**  
![Sales Trends](images/sales_trends.png)  

🚘 **Car Model Performance**  
![Car Models](images/car_models.png)  

🌍 **Regional Insights**  
![Regional Insights](images/region_insights.png)  

---

## 🚀 How to Run This Project  
1. Clone/download this repository  
2. Run **Car_Sales_Cleaning.sql** and **Car_Sales_KPIs.sql** in your SQL environment  
3. Open **car_sales_analysis.pbix** in Power BI Desktop  
4. Explore interactive dashboards for insights  

---

## 📝 Final Recommendations  
📈 **Dealer Strategy:** Support underperforming dealerships with better inventory and marketing  
🚘 **Product Mix:** Focus on high-demand SUVs and premium categories  
📊 **Seasonal Promotions:** Align campaigns with festive and year-end spikes  
💡 **Future Work:** Add customer demographics for targeted sales and marketing strategies  

---

## 👤 Author & Contact  
**T V Shreyas Kumar**  

💼 LinkedIn: [www.linkedin.com/in/shreyas-kumar]
✉️ Email: **Shreyas291103@gmail.com**  
