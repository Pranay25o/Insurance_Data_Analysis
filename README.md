# 🛡️ Insurance Data Analysis Dashboard (Power BI)

### 🔗 Dashboard Tool
👉 Microsoft Power BI

---

## 📌 Problem Statement

Insurance organizations manage large volumes of data related to **policies, premiums, claims, customers, and coverage amounts**.  
This dashboard provides a **centralized analytical view** to help business users and analysts monitor insurance performance, identify trends, and make informed decisions.

Through this dashboard, users can:
- Track **total premium, coverage, and claim amounts**
- Monitor **active vs inactive policies**
- Analyze **claims by status and age group**
- Compare performance across **policy types**
- Understand customer behavior and risk patterns

---

## 📊 Dashboard Preview

![Insurance Dashboard](images/insurance-dashboard.png)

> 📌 *Upload the dashboard screenshot as `insurance-dashboard.png` inside the `images/` folder*

---

## 📂 Dataset Description

- **Source:** Insurance transactional data  
- **Format:** CSV / Excel  
- **Type:** Business / Sample Dataset  

### Key Fields:
- Policy Number  
- Claim Number  
- Customer ID  
- Gender  
- Policy Type (Auto, Health, Travel, Life, Home)  
- Premium Amount  
- Coverage Amount  
- Claim Amount  
- Claim Status (Pending, Rejected, Settled)  
- Age Group  

---

## 🔄 Data Architecture & Connectivity

This project follows a **standard Power BI enterprise architecture**:

### 🔹 Data Flow
1. **ODBC Connection**
   - Data sourced from a MySQL database using **ODBC DSN**
   - Connected via **On-Premises Data Gateway**

2. **Semantic Model (Power BI Dataset)**
   - Data cleaned and transformed using **Power Query**
   - Business logic implemented using **DAX**
   - Centralized dataset used across reports

3. **Power BI Report**
   - Interactive visuals built on top of the semantic model
   - Filters and slicers for dynamic analysis

### 🔗 Architecture Diagram

![Insurance Dashboard](https://github.com/Pranay25o/Insurance_Data_Analysis/blob/main/Dashboard.png?raw=true)

---

## 🧹 Data Cleaning (Power BI – Power Query)

Data preparation was performed using **Power Query Editor**:

- Removed duplicate records  
- Handled missing and null values  
- Standardized column names  
- Converted data types (numeric, text, date)  
- Created **age group categories**  
- Filtered invalid or inconsistent records  

---

## 📐 DAX Measures Used

DAX (Data Analysis Expressions) was used to create dynamic KPIs and calculations:

- Total Premium Amount  
- Total Coverage Amount  
- Total Claim Amount  
- Active Policy Count  
- Inactive Policy Count  
- Claim Count by Status  
- Gender-wise Policy Count  
- Claim Amount by Age Group  

These measures enable **interactive filtering and real-time insights**.

---

## 📊 Dashboard Components

### 🔹 KPI Cards
- Total Premium Amount  
- Total Coverage Amount  
- Total Claim Amount  

### 🔹 Premium Amount by Policy Type
- Travel  
- Health  
- Auto  
- Life  
- Home  

### 🔹 Active vs Inactive Policies
- Donut chart showing policy distribution  

### 🔹 Claims by Claim Status
- Rejected  
- Settled  
- Pending  

### 🔹 Claim Amount by Age Group
- Young Adults  
- Adults  
- Elder  

### 🔹 Detailed Policy Table
- Policy Type vs Pending, Rejected, and Settled claim amounts  

---

## 🔧 Steps Followed

1. Connected MySQL database using ODBC  
2. Configured On-Premises Data Gateway  
3. Imported data into Power BI Desktop  
4. Cleaned and transformed data using Power Query  
5. Created calculated columns and **DAX measures**  
6. Designed KPI cards for high-level metrics  
7. Built bar, donut, line, and area charts  
8. Added slicers for Policy Number, Claim Number, and Customer ID  
9. Applied consistent dark theme for readability  
10. Optimized layout and visual alignment  
11. Validated insights using filters and slicers  
12. Finalized dashboard for business analysis  

---

## 📈 Key Insights

- Travel and Health policies generate the highest premium amounts  
- Majority of policies are **active**, indicating strong retention  
- Settled claims dominate compared to pending claims  
- Adults contribute the highest claim amount among age groups  
- Claim behavior varies significantly across policy types  

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- MySQL  
- ODBC  
- On-Premises Data Gateway  
- Excel / CSV  

---

## 👤 Author

**Pranay Ogale**  
Aspiring Data Analyst | Power BI | Tableau | SQL  

🔗 LinkedIn: https://www.linkedin.com/in/pranay-ogale/
