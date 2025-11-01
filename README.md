# 🚗 Insurance Risk & Claim Analysis — Data Analytics Project

## 📘 Project Overview
The **Insurance Risk & Claim Analysis** project explores key insights from a large insurance dataset to understand customer demographics, vehicle information, and claim behavior.  
The project demonstrates the complete **data analytics lifecycle** — from **exploratory data analysis (EDA)** in Python to **interactive visualization** in Power BI.

The goal of this project was to:
- Identify risk patterns and claim trends across various demographics.  
- Understand how education, marital status, and driving factors affect claims.  
- Present data-driven insights in an interactive and business-friendly dashboard.

---

## 🧩 Tools & Technologies
- **Python (EDA & Statistical Analysis)**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Power BI (Dashboard Design & Insights)**
- **Microsoft Fabric (for hosting & sharing the dashboard)**

---

## 📊 Dataset Description

| Feature | Description |
|----------|-------------|
| `Customer ID` | Unique identifier for each policyholder |
| `Gender`, `Age`, `Marital Status`, `Education` | Customer demographics |
| `Car Make`, `Car Model`, `Car Year`, `Car Use` | Vehicle details |
| `Coverage Zone` | Area type (Urban, Rural, Suburban, Highly Urban) |
| `Household Income`, `Kids Driving` | Socio-economic features |
| `Claim Amount`, `Claim Frequency` | Details of insurance claims |
| `Parent` | Whether the customer has dependent kids |

**Total Records:** 37,542  
**Total Columns:** 16  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ Data Overview
- Dataset has **37,542 records** with no missing values.  
- Data types include categorical (10), numerical (3), and date (1).  
- Data cleaning and transformation performed using **Pandas**.

### 2️⃣ Key Observations
- **Average Claim Amount:** \$5,037  
- **Average Claim Frequency:** 0.51  
- **Private car policies** dominate the dataset (~30K vs 7K commercial).  
- **Coverage Zones** are nearly equally distributed (Urban, Rural, etc.).  

### 3️⃣ Claim Patterns
- **Highest Claim Exposure:**  
  - Urban regions  
  - Customers aged **36–55**  
  - Private car owners  
- **Lowest Claim Exposure:**  
  - Rural and Highly Rural customers  

### 4️⃣ Education & Marital Status vs Claims

| Education | Divorced | Married | Separated | Single | **Total Claim ($M)** |
|------------|-----------|----------|------------|---------|----------------|
| High School | 2.87 | 5.24 | 3.52 | 40.17 | **51.8** |
| Bachelors | 16.53 | 31.10 | 7.67 | 38.72 | **93.9** |
| Masters | 4.65 | 9.50 | 2.22 | 11.93 | **28.3** |
| PhD | 2.33 | 4.79 | 1.11 | 5.46 | **13.7** |

📈 **Insight:** Singles and Bachelor’s degree holders have the **highest total claims**, indicating potentially higher risk behavior.

### 5️⃣ Kids Driving Impact
- Families with **no kids driving** show the **highest total claim (\$134M)**.  
- Claim amounts decrease sharply as the number of kids driving increases.

---

## 📈 Power BI Dashboard

### **Dashboard Title:** Insurance Risk & Claim Analysis

**Key Metrics Displayed(KPI's)**
- 🧾 **Total Policies:** 37,542  
- 💵 **Total Claim Amount:** \$187.8M  
- 🔁 **Average Claim Frequency:** 0.51  
- 👨‍🦰 **Male Policies:** 18.7K | 👩 **Female Policies:** 18.8K  

**Visuals Used in Dashboard**
1. **KPI Cards:** Total Policies, Total Claim, Avg Claim  
2. **Donut Charts:** Policies by Car Use, Education, Coverage Zone  
3. **Bar Charts:** Policies by Age Group, Car Make, Kids Driving  
4. **Line Chart:** Policies by Car Year  
5. **Matrix/Table:** Claim distribution by Education & Marital Status  

**Major Insights**
- Ford and Chevrolet dominate among car makes.  
- Private cars and urban policyholders contribute the most to total claims.  
- Claim frequency is steady over time, but claim amounts vary with age and income.  
- Bachelor’s and Single policyholders represent the highest financial risk group.

---

## 💡 Results & Business Insights
- **Urban regions** and **private car owners** are more prone to higher claim amounts.  
- **Middle-aged (36–55)** customers are the most active policyholders.  
- **Families with kids driving** tend to have fewer claims, implying safer households.  
- The combination of **education level** and **marital status** shows clear behavioral risk patterns.  
- The **Power BI dashboard** effectively communicates trends for strategic insurance decision-making.


