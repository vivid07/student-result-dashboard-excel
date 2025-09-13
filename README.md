# student-result-dashboard-excel
Designed an Excel dashboard on multi-year student results (2021–2024) to analyze pass rates, grade distributions, and student performance trends, enabling data-driven academic insights.

📌 Project Overview

This project analyzes and visualizes student registration and examination results from 2021–2024.
The goal was to consolidate fragmented CSV/Excel files into a single clean dataset, and then design a professional Excel dashboard that provides meaningful insights for administrators.

Key objectives:

📂 Unify registration & results data into a structured dataset

🧹 Clean & validate data (remove duplicates, fix formatting, handle absentees)

📊 Build a dashboard that answers core academic questions

⚡ Reduce manual effort with automated summaries in Excel

🛠 Tech Stack

Excel (PivotTables, Power Query, Charts, Dashboard Design)

GitHub (version control & project sharing)

❓ Key Questions Answered by the Dashboard

The dashboard provides clear answers to the following academic and administrative questions:

📈 Pass Rate Analysis

What is the overall pass percentage?

Which modules have the highest or lowest pass rates?

🏷️ Grade Distribution

How are grades (A/B/C/D/F/ABS) distributed across each module?

Are there modules with unusually high failure/absence rates?

🧑‍🎓 Student Performance

How many students have cleared all modules?

How many students have partially cleared vs. failed all modules?

🔁 Attempt Behavior

On average, how many modules does each student attempt?

What is the distribution of students attempting 1, 2, 3, 4+ modules?

📌 Administrative Insights

Which modules may need curriculum support or intervention due to low performance?

What proportion of results are absentees versus active attempts?

📊 Dashboard Features

Pass Rate by Module (Column Chart)

Grade Distribution by Module (Stacked Column Chart)

Student Status Overview (Pie Chart: Cleared / Partial / Failed)

Modules Attempted per Student (Column Chart)

📂 Repository Structure
student-results-dashboard/
│
├── data/
│   └── Merged_Results.xlsx              # (Sample / anonymized dataset)
│
├── output/
│   └── Merged_Results_Dashboard.xlsx    # Final Excel Dashboard
│
├── README.md                            # Project documentation
└── LICENSE                              # MIT or similar open license

🚀 How to Use

Clone this repo:

git clone https://github.com/<your-username>/student-results-dashboard.git
cd student-results-dashboard


Open output/Merged_Results_Dashboard.xlsx in Excel.

The Dashboard sheet contains key visualizations.

Other sheets (Data_Clean, Summaries) contain underlying tables.

📷 Sample Dashboard Screenshot

<img width="1447" height="484" alt="image" src="https://github.com/user-attachments/assets/d66ae61c-22a9-4e3b-be6f-1da304ba06dd" />
</br>
<img width="1341" height="560" alt="image" src="https://github.com/user-attachments/assets/ddfad653-fbc4-45da-8821-7b245a9bd773" />



🔮 Future Enhancements

Add interactive slicers (filter by module, grade, student).

Build a Power BI / Tableau version of the dashboard.

Extend analytics to trend analysis across years.

Automate raw file ingestion directly from exam office exports.

📌 Key Learnings

Hands-on experience in data cleaning & preprocessing in Excel.

Applying data analytics using Excel & SQL.

Designing a user-friendly dashboard for non-technical stakeholders.

Translating raw academic data into actionable insights.
