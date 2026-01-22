# 🎓 MBA Admission & Placement Analytics
### *Recruitment Strategy | Educational Data Mining | Power BI*

## 🚀 Project Overview
**Objective:** To analyze the academic and placement profile of the MBA batch at IMS DAVV.
**Scope:** Processed real-world data for **894 students** and **232 job selections** to derive actionable recruitment insights.

## 💡 Key Insights
* **Placement Rate:** Visualized a **26% selection rate**, with Top Recruiters being **Deloitte (33)** and **ICICI Securities (23)**.
* **Salary Analysis:** Calculated **Average CTC** and **Highest CTC (19 LPA)**.
* **Batch Diversity:** Identified a 51% dominance of CBSE board students and an average age of 25 years.

## 🛠️ Technical Stack
* **Tool:** Microsoft Power BI
* **Data Modeling:** Star Schema (Fact Tables: Placements | Dimension Tables: Students, Branch).
* **DAX Measures:**
    * `Avg Package = AVERAGE(Placement[CTC])`
    * `Placement Ratio = DIVIDE([Selected Students], [Total Students])`
