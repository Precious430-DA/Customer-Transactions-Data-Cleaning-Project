# 🧹 Customer Transactions Data Cleaning Project

## 📌 Overview
This project focuses on cleaning and preparing a **20,000-row customer transactions dataset** for analysis.  
The raw data contained:
- **128,000+ missing values**
- **38 irregular columns**
- Inconsistent date formats (`DD/MM/YYYY` vs `MM/DD/YYYY`)
- Numeric fields stored as text
- Messy text formats and redundant fields

After cleaning:
- ✅ Missing values reduced from **128,779 → 0**
- ✅ Schema reduced from **38 → 31 columns**
- ✅ Dates stored as proper datetime
- ✅ Numeric values properly typed (`int`, `float`)
- ✅ Text/categorical fields standardized (`category` dtype)
- ✅ No duplicates
- ✅ Final quality score: **96/100**

---

## 🔧 Methods & Tools
### Tools Used
- **Microsoft Excel** (primary cleaning)  
  - `IF`, `IFNA` → replace missing values and condition-based cleaning  
  - `LEFT`, `RIGHT`, `MID`, `FIND` → extract and restructure embedded values  
  - `PROPER` → standardize text case  
  - **Nested formulas** for advanced logic  

---

## 📊 Results
- **Rows:** 20,000  
- **Columns:** 31 (clean schema)  
- **Nulls:** 0  
- **Duplicates:** 0  
- **Data Quality Score:** 96/100  

The dataset is now **analysis-ready** and supports:
- Exploratory Data Analysis (EDA)  
- Business Intelligence Dashboards (Power BI, Tableau)  
- Predictive Modeling and Machine Learning  

---

## 📂 Repository Structure
