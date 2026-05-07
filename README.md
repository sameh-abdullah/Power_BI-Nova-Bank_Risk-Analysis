# 🏦 Nova Bank Risk Analysis Dashboard (Power BI)

## 📌 Overview
This project presents an interactive **Power BI dashboard** for Nova Bank, Risk analysis. It is designed to find the right balance and to help the bank understand who tends to default and why, and how lending decisions can be made more reliable.

The dashboard tells the story of loan amount across different dimensions, identifies trends, and helps stakeholders make data-informed decisions.

---

## ❗Key Questions to Answer in the Analysis:

-	Which types of borrowers are more likely to default?
-	Do certain loan purposes (education, medical, personal, debt consolidation) carry more risk?
-	How do loan-to-income and debt-to-income ratios relate to repayment?
-	Does employment type or home ownership make a difference?
-	How do past defaults or longer credit histories affect loan outcomes?
-	Are there clear differences between borrowers in the USA, UK, and Canada?
-	Which loan grades or terms seem safer, and which are riskier?
-	Can groups of borrowers be identified that look “safe” versus “risky”?


---

## 📂 Dataset
- **Source:** Excel file (`Credit_Risk_Dataset.xlsx`)
- **Main Table:** `Credit_Risk_Data`

## 📝 Key Features
- Total patients, total bills, and average service time tracking
- Year-over-year comparisons for patients and billing
- Percentage-to-average metrics and color-coded performance indicators
- Age category, blood type, and medical condition analysis
- Hospital, doctor, medication, and insurance provider filtering
- Date-based analytics with admission and discharge date support
- Dynamic parameter selection for bill amount vs. average service time
- Geographic support via hospital latitude and longitude fields 

---

## 🧠 Data Model
Star schema with a fact table and lookup tables
---

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query** (Data Cleaning & Transformation)
- **DAX (Data Analysis Expressions)** for measures and calculations
- **Excel** (Data Source)

---

## 📈 Dashboard Features
- Interactive filter (city, defualted, history length, loan term months)
- KPI cards for quick insights
- Comparative analysis
- Visualizations:
  - KPIs
  - Bar charts  
  - Pie charts  
  - Trend analysis  
  - Distribution visuals
  - Map

---

## 🖼️ Dashboard Preview
**Interactive Dashboard** <a href="https://app.powerbi.com/view?r=eyJrIjoiMTZkY2Y0N2UtMzg4MS00MzQ2LTg5YzgtMTc2MzIxYjUxZDI2IiwidCI6IjE1ODgyNjJkLTIzZmItNDNiNC1iZDZlLWJjZTQ5YzhlNjE4NiIsImMiOjh9"> Nova Bank risk analysis Dashboard</a></br>

**Project Dashboard Image**
<pdf src="https://github.com/sameh-abdullah/Power_BI-Nova-Bank_Risk-Analysis/blob/main/Docs/Cred_Risk_challenge%20PowerBI_V02.pdf" width="1000"/></br>

---

## 📁 Project Structure
 ├── Dataset/ <a href="Dataset">Dataset</a> <br>
 ├── Docs/ <a href="Docs">Docs</a> <br>
 ├── Reports template/ <a href="Report template"> Power BI file (.pbit)</a> <br>
 └── README.md


---

## 🎯 Project Value
This project demonstrates:
- Data modeling in Power BI  
- Use of DAX for analytical calculations  
- Building interactive dashboards  
- Translating raw data into meaningful insights
--------
## Architecture Notes
- The dashboard uses a clean star-schema architecture.
- Lookup tables normalize dimension data and improve filtering behavior.
- Measures are centralized in `_MeasuresTable` for easier maintenance.
- Date analysis is driven by a calculated `DateTable` rather than direct date columns.
- The model supports dynamic selections and parameter-driven report views.  

---

## 👤 Author
**Sameh Abdullah**  
**LinkedIn**: <a href="https://linkedin.com/in/sameh-abdullah-961554176"> My Profile </a> 

---

