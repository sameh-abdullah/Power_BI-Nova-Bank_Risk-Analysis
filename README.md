# 🏦 Nova Bank Risk Analysis Dashboard (Power BI)

## 📌 Overview
This project presents an interactive **Power BI dashboard** for healthcare analysis. It is designed to uncover insights that can drive better healthcare decisions, optimize costs, and improve patient outcomes.

The dashboard tells the story of patient care across hospitals, identifies trends, and helps stakeholders make data-informed decisions.

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
- **Source:** Excel file (`Healthcare Analysis Dataset.xlsx`)
- **Main Table:** `healthcareData`

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
- Interactive filter (year)
- KPI cards for quick insights
- Comparative analysis
- Visualizations:
  - KPIs
  - Bar charts  
  - Pie charts  
  - Trend analysis  
  - Distribution visuals

---

## 🖼️ Dashboard Preview
**Interactive Dashboard** <a href="https://app.powerbi.com/view?r=eyJrIjoiMTZkY2Y0N2UtMzg4MS00MzQ2LTg5YzgtMTc2MzIxYjUxZDI2IiwidCI6IjE1ODgyNjJkLTIzZmItNDNiNC1iZDZlLWJjZTQ5YzhlNjE4NiIsImMiOjh9"> Nova Bank risk analysis Dashboard</a></br>

**Project Dashboard Image**
<img src="https://github.com/sameh-abdullah/Power_BI-Healthcare-Analytics/blob/main/docs/Healthcare%20DB_p1.png" width="1000" heigh="1000"/></br>

<img src="https://github.com/sameh-abdullah/Power_BI-Healthcare-Analytics/blob/main/docs/Healthcare%20DB_p2.png" width="1000" heigh="1000"/>

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

