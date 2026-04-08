Practical_Exam_11156

📂 DATASETS USED:

1. Students.xlsx
2. Scores.xlsx
3. Attendance.xlsx
4. Behavior.xlsx

---

🧹 DATA PREPARATION:

* Loaded all Excel files into Power BI
* Cleaned data using Power Query:

  * Fixed column names
  * Set correct data types
  * Handled missing values
* Applied "Close & Apply"

---

🔗 DATA MODELING:

* Created relationships:
  Students[StudentID] → Scores[StudentID]
  Students[StudentID] → Attendance[StudentID]
  Students[StudentID] → Behavior[StudentID]
* Used One-to-Many relationships

---

📐 DAX MEASURES CREATED:

* % Score
* Avg Score
* Attendance %
* Behavior Count
* Total Students
* Performance Category (High/Medium/Low)

---

📊 VISUALIZATIONS CREATED:

1. Cards (KPIs):

   * Total Students
   * Average Score
   * Attendance %

2. Bar Chart:

   * Subject vs Average Score
   * Class-wise comparison

3. Line Chart:

   * Performance trend by Term

4. Donut Chart:

   * Behavior distribution

5. Table:

   * Student Name, Subject, Score, % Score
   * Conditional formatting applied

---

🎨 CONDITIONAL FORMATTING:

* Applied on % Score:

  * Green → High (≥80)
  * Yellow → Medium (40–80)
  * Red → Low (<40)

---

📄 REPORT PAGES:

1. DASHBOARD:

   * KPI Cards
   * Bar Chart, Line Chart, Donut Chart
   * Slicers (Class, Section, Subject, Term)

2. STUDENT DETAILS:

   * Drillthrough enabled
   * Student Name card
   * Attendance %, Avg Score, Performance
   * Table and behavior chart

3. SCORE DETAILS:

   * Detailed analysis
   * Class & Subject performance charts
   * Top students and filtered table

---

🔍 INTERACTIVITY:

* Slicers for filtering
* Drillthrough for student-level analysis
* Page navigation using buttons
* Tooltips and bookmarks (optional)

---

🎨 DESIGN FEATURES:

* Clean layout with proper alignment
* Consistent color theme
* Card-based KPI display
* User-friendly interface

---

🏁 CONCLUSION:
This project demonstrates skills in:

* Data cleaning and modeling
* DAX calculations
* Data visualization
* Dashboard design
* Interactive reporting

The final dashboard provides clear insights into student performance and helps in decision-making.

---
