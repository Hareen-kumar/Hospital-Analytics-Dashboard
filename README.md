# 🏥 Hospital Analytics Dashboard – Power BI Project

This Power BI dashboard provides a detailed analysis of hospital data focusing on patient admissions, discharges, treatment costs, feedback scores, department-wise trends, and more.

---

## 📊 Dashboard Preview

![image](https://github.com/user-attachments/assets/b691c1de-8d19-41c1-b744-85bc7ab38db6)
 <!-- Optional if you're adding screenshot -->

---

## 🛠️ Project Tasks Performed

### 🔹 1. **Data Cleaning & Preparation (Power Query)**
- Removed trailing spaces using `Text.Trim`
- Converted inconsistent date formats to standard `dd-mm-yyyy`
- Extracted **Admission Month** and **Discharge Month**
- Created custom columns for:
  - **Length of Stay (Days)**
  - **Month Number** for sorting visuals
  - **Age Groups** using conditional column logic
- Rounded down treatment cost values
- Removed nulls and verified data types

### 🔹 2. **Data Modeling**
- Ensured proper relationships (1 table only, flat model)
- Created **new measures** for:
  - Average Stay Duration
  - Total Revenue
  - Average Age
  - Recovery Rate

### 🔹 3. **Dashboard Design**
Built an interactive dashboard with slicers, cards, and visuals including:
- **Line Chart** – Admissions vs Discharges by Month
- **Pie Chart** – Patients by Age Group
- **Donut Chart** – Patient Recovery Status
- **Bar Chart** – Feedback Score vs Patient Count
- **Treemap** – Patient Count by Diagnosis
- **Bar Chart** – Department-wise Patient Count
- KPIs: Total Patients, Avg Stay, Avg Age, Total Revenue

### 🔹 4. **User Experience**
- Added slicers for Year and Gender filters
- Consistent color palette (pink/purple branding)
- Tooltip enhancements & interactive legends

---

## 📂 Files Included

| File Name                      | Description                             |
|-------------------------------|-----------------------------------------|
| [Hareen_Kumar_Healthcare.pbix ](https://github.com/Hareen-kumar/Hospital-Analytics-Dashboard/blob/main/Hareen%20kumar%20G.pbix)| Power BI dashboard file                 |
| [Simulated_Hospital_Data.csv ](https://github.com/Hareen-kumar/Hospital-Analytics-Dashboard/blob/main/Simulated_Hospital_Data.csv) | Source hospital dataset (500 patients)  |
| [dashboard_screenshot.png ](https://github.com/Hareen-kumar/Hospital-Analytics-Dashboard/blob/main/Screenshot%202025-07-08%20155152.png)   | Dashboard screenshot (optional)         |
| `README.md`                   | Project documentation                   |

---

## 🧠 Tools Used

- **Microsoft Power BI**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- Excel (Initial preview and edits)

---

## 👨‍⚕️ Insights Delivered

- Monthly pattern of admissions and discharges
- Recovery trends and feedback analysis
- Department-wise load & treatment types
- Average age and revenue analysis

---

## 📌 Author

**Hareen Kumar G**  
_Data Analyst  | Power BI Enthusiast | MBA – Data Science_



---

