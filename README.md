# Uber_Data_Analysis
This project presents an interactive Power BI dashboard that uncovers insights from Uber ride data. The dashboard enables quick and intuitive analysis of rides, revenues, cancellations, payment methods, and customer experience.

# 🚖 Uber Rides Data Analysis Dashboard  

## 📌 Project Overview  
This project demonstrates an **end-to-end data pipeline** using **SQL, Python, and Power BI** to analyze Uber rides data.  
It covers **data extraction, cleaning, transformation, and visualization**, resulting in an **interactive dashboard** that provides business insights.  

---

## 🛠️ Tools & Technologies  
- **SQL (MySQL Workbench)** → Data storage, queries, and creation of views.  
- **Python (Pandas, Jupyter/Colab)** → Data cleaning and preprocessing.  
- **Power BI** → Dashboard creation and visualization.  

---

## 📂 Project Workflow  
1. **Data Source**  
   - Imported raw Uber rides dataset into MySQL.  

2. **Database & Views (SQL)**  
   - Designed schema and created tables (`bookings`, `customers`, `drivers`).  
   - Built SQL views such as:  
     - `Successful_Bookings`  
     - `Cancelled_By_Driver`  
     - `Cancelled_By_Customer`  

3. **Data Cleaning (Python)**  
   - Connected MySQL with Python.  
   - Cleaned missing values, removed duplicates, standardized column formats.  
   - Exported cleaned tables/views to CSV for visualization.  

4. **Visualization (Power BI)**  
   - Designed an **interactive dashboard** with key KPIs:  
     - ✅ Total Bookings  
     - ✅ Success vs Cancellations (by driver & customer)  
     - ✅ Rides by City & Time  
     - ✅ Revenue insights  

---

## 📊 Dashboard Highlights  
- Drill-through & filters for detailed analysis.  
- Comparison of driver vs customer cancellations.  
- Geographic insights for ride distribution.  
[Overall Dashboard](https://github.com/Amaregoud/Uber_Data_Analysis/blob/main/Screenshot%202025-09-14%20112503.png)
---

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Amaregoud/Uber_Data_Analysis.git


👨‍💻 Author

Amaregouda Patil
📧 amaregouda449@gmail.com

🌐 https://www.linkedin.com/in/amaregouda-patil-51869425b/


