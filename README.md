# 💼 Workforce360 – HR Attrition Analytics Dashboard

### 📊 Overview
The **Workforce360 HR Attrition Dashboard** analyzes employee attrition trends and provides data-driven insights for workforce planning.  
It demonstrates an end-to-end workflow using **Python (data prep)**, **SQL (data modeling)**, and **Power BI (visualization)**.

---

## ⚙️ Tech Stack
| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy)** | Initial data cleaning and inspection |
| **MySQL** | Data storage and KPI analysis |
| **Power BI** | Interactive dashboard and storytelling |

---

## 📁 Project Workflow
1. **Data Preparation (Python)**  
   - Loaded dataset, checked for nulls/duplicates (None found).  

2. **Data Modeling & Analysis (SQL)**  
   - Created tables (`employee_attrition`, `overall`, `salary_band`).  
   - Calculated key KPIs (attrition %, tenure, employee count).  

3. **Visualization (Power BI)**  
   - Built 2-page dashboard with KPIs and interactive filters.  
   - Added relationships for dynamic filtering across tables.

---

## 🧮 Key Insights
- **Overall Attrition Rate:** 16.12 %  
- **Total Employees:** 1,470  
- **Employees Left:** 237  
- **Average Tenure:** 18.38 years  

### Attrition Drivers
- Highest attrition in Sales and R&D departments.  
- Overtime workers show higher attrition.  
- Low and Medium salary bands have greater turnover.  
- Majority leaving are aged 25 – 34.

---

## 🖥️ Dashboard Preview
📸 **Snapshot:**  
![Workforce360 Dashboard](images/Dashboard_Page1.png)

---

## 🧩 Data Model
- **Fact Table:** `employee_attrition`  
- **Dimension Tables:** `overall`, `department`, `salary_band`  
- Relationships on `EmployeeNumber`, `Department`, `SalaryBand`.

---

## 🧠 Learnings
- Practiced full ETL pipeline from raw data to dashboard.  
- Strengthened SQL aggregation and joins.  
- Learned Power BI data-modeling and storytelling principles.

---
## 🧰 Files in Repository

📦 **Workforce360-HR-Attrition**
├── 📂 **dataset/**
│   ├── HR_Analytics.csv  
│   └── README_dataset.txt  
│
├── 📂 **python_notebook/**
│   └── HR_Data_Cleaning.ipynb  
│
├── 📂 **sql_scripts/**
│   ├── create_tables.sql  
│   ├── data_insertion.sql  
│   └── analysis_queries.sql  
│
├── 📂 **images/**
│   ├── Dashboard_Page1.png  
│   └── Dashboard_Page2.png  
│
├── Workforce360_HR_Attrition.pbix  
└── README.md



---

## 👩‍💻 Author
**Anushka Gupta**  
📍 Data Analyst | Business Analyst | SQL Developer  
🔗 [Portfolio Website](https://anushkagupta0203.github.io/)  
💼 [LinkedIn](https://www.linkedin.com/in/anushkagupta23/)

⭐ If you find this project helpful, please star the repository!

