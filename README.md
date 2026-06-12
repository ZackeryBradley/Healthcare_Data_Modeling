# 🏥 Healthcare Data Model Explorer  

## 📌 Overview  
This project builds a **star schema data model** using a healthcare dataset and powers an interactive Streamlit dashboard for analytical exploration and reporting.

---

## ❓ Business Problem  
How can we transform raw healthcare data into a structured, scalable model that enables **fast, flexible, and business-ready analytics**?

---

## 🛠 Tools Used  
- Python (Pandas)  
- Streamlit  
- Plotly (Data Visualization)  
- Data Modeling  
- Star Schema Design  
- Custom CSS Styling  

---

## 🧱 Data Model  

### 🟦 Fact Table  
- **Fact Admissions**  
  - Stores admission-level records including billing amount and foreign keys to all dimensions  

### 🟩 Dimension Tables  
- **Patient Dimension**  
  - Name, Age, Gender, Blood Type  

- **Doctor Dimension**  
  - Unique doctor records  

- **Hospital Dimension**  
  - Hospital-level information  

- **Insurance Dimension**  
  - Insurance provider details  

- **Condition Dimension**  
  - Medical condition categories  

- **Date Dimension**  
  - Year, Quarter, Month, Day breakdown  

---

## 📊 Analytical Capabilities  

- Executive dashboards (Admissions, Billing, Trends)  
- Slice & dice analysis across multiple dimensions  
- KPI tracking (Total Billing, Avg Billing, Patient Counts)  
- Data quality and completeness checks  
- Star schema table exploration  

