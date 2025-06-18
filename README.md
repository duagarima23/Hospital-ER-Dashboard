# 🏥 Hospital Emergency Room Dashboard

📊 **Project Overview**  
The **Hospital Emergency Room Dashboard** is an interactive Power BI analytics solution that visualizes 19 months of emergency room data. It provides comprehensive insights into patient volumes, demographics, departmental referrals, admission trends, wait times, and satisfaction levels. This dashboard helps hospital administrators and analysts make data-informed decisions to improve patient care and operational efficiency.

---

🔧 **Technologies Used**

- **Power BI Desktop**: For building dynamic dashboards and interactive reports  
- **Power Query (M language)**: For data cleaning, shaping, and transformation  
- **DAX (Data Analysis Expressions)**: For creating measures, KPIs, and calculated fields  
- **CSV (Excel)**: Used as the structured data source  

---

🗃️ **Dataset Structure**

The dataset is stored in a CSV format and includes fields such as:

- `Patient ID`: Unique alphanumeric identifier  
- `Gender`, `Age`, `Race`: Patient demographic data  
- `Admission Status`: Indicates whether the patient was admitted  
- `Wait Time`: Time before first medical contact  
- `Satisfaction Score`: Patient feedback on a 10-point scale  
- `Department Referral`: Referred department (if any)  
- `Admission Date`: Date of ER visit  

---

📈 **Key Features & Visuals**

- **Monthly View Dashboard**: Trends in patient flow, satisfaction, wait times, and admission rates month-by-month  
- **Consolidated View**: Aggregated analysis across the entire date range  
- **Patient Details Table**: Row-level data for detailed review  
- **Key Metrics**:
  - % of patients seen within 30 minutes
  - No. of referrals by department
  - Age and race demographics
  - Admission vs non-admission trends

---

🔍 **Insights Derived**

- ~50% of patients were admitted, indicating high ER utilization  
- Average wait time is ~35.3 minutes, with moderate satisfaction (avg. score ~4.99/10)  
- General Practice and Orthopedics are the top referral departments  
- Peak volume days: Mondays and Saturdays; busiest hours: 11 AM, 1 PM, 7 PM  
- Adults aged 30–39 were the most frequent ER visitors  

---

🧠 **Skills Demonstrated**

- Data modeling and KPI creation in Power BI  
- Building interactive multi-page dashboards  
- Slicer-based filtering and cross-report drill-through  
- Analyzing healthcare performance and operational bottlenecks  
- Effective use of visuals to tell data stories  

---

⚙️ **How to Run**

1. Clone or download this repository  
2. Open `Hospital ER Dashboard.pbix` in **Power BI Desktop**  
3. Review or refresh the data using `Hospital ER_Data.csv` (already linked in PBIX)  
4. Navigate through the dashboards:
   - **Monthly View**
   - **Consolidated View**
   - **Patient Details**
   - **Key Takeaways**

---

📎 **Resources Included**

| File Name                     | Description                            |
|------------------------------|----------------------------------------|
| `Hospital ER Dashboard.pbix` | Power BI file with complete dashboard  |
| `Hospital ER Dashboard.pdf`  | Exported version of the report in PDF  |
| `Hospital ER_Data.csv`       | Raw dataset used in the dashboard      |
