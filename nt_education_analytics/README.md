# NT Education Attendance Analytics Dashboard
### Government & Operational Analytics

This project analyzes school attendance patterns across the Northern Territory using publicly available government data to identify declining trends, regional disparities, and opportunities for earlier intervention. It is designed to reflect the kind of reporting and decision support used in public-sector education environments [web:8][web:12].

> **Project focus:** Turning attendance data into actionable insights for school leaders, regional managers, and policy teams responsible for improving student engagement and attendance outcomes [web:8][web:12].

---

## Business problem

School attendance is a major operational and policy issue in the Northern Territory, particularly in remote and regional communities. NT reporting shows attendance data is collected regularly from enrolment and attendance datasets, and recent public reporting indicates attendance remains low enough to require ongoing intervention and monitoring [web:19][web:12].

This project was built to answer three practical questions:

- Which schools or regions are experiencing the steepest attendance declines?
- Where are attendance gaps most pronounced across the NT?
- What metrics would help leaders intervene earlier and more effectively?

---

## What the project does

The dashboard provides a structured view of attendance performance across schools and regions. It is intended to help identify patterns, compare geographies, and present data in a format that supports executive reporting and frontline planning [web:8][web:19].

Key outputs include:

- Attendance trend analysis by school and region.
- Identification of underperforming geographic clusters.
- KPI reporting for operational review.
- A dashboard format suitable for executive and stakeholder use.

---

## Data and methods

| Analytical layer | What was done |
|---|---|
| Data ingestion & ETL | Cleaned and structured NT government education datasets using Python and pandas [web:8]. |
| Relational modeling | Built an analytical schema in PostgreSQL to support reporting logic and reusable queries. |
| Dashboarding | Developed Power BI views for operational reporting and KPI monitoring. |

The project uses public NT Government education datasets, including enrolment and attendance reporting, which are published through the NT open data portal [web:8][web:19]. The design reflects the fact that attendance remains a live public-sector issue in the Territory rather than a one-off analysis exercise [web:12][web:21].

---

## Key insights

Add your real findings here once finalised. Strong portfolio examples should be specific and quantified.

- Attendance is lowest in remote or high-need regions.
- A small number of schools account for a disproportionate share of attendance decline.
- Some regions show improvement after intervention periods.
- Attendance gaps are large enough to justify targeted support rather than generic interventions.
- Dashboard filtering by region, school, and term helps users move from overview to action.

If possible, replace these with measured findings from your analysis, such as percentage-point gaps, top/bottom-ranked regions, or trend changes over time.

---

## Dashboard walkthrough

Include screenshots and short explanations for each page of the dashboard.

1. **Overview page**: NT-wide attendance rate, year-on-year movement, and headline KPIs.
2. **Regional view**: Comparison by region, with maps or bar charts.
3. **School view**: School-level drilldown and ranking.
4. **Trend view**: Attendance over time by term or semester.
5. **Intervention view**: Schools or clusters flagged for attention.

This helps a recruiter see that you understand how executives and analysts actually use dashboards in government settings.

---

## Technical stack

- **Python** for data cleaning, transformation, and preparation.
- **pandas** for ETL and feature creation.
- **PostgreSQL** for relational modeling and reporting queries.
- **Power BI** for dashboarding and executive reporting.
- **SQL** for analysis and data validation.

Keep this section practical and concise. Recruiters care more about how you used the tools than the logos themselves.

---

## Limitations and assumptions

- The project uses publicly available data and may not include all operational or contextual variables.
- Attendance outcomes may be influenced by factors not visible in the dataset, such as family mobility, weather, staffing, or community access.
- Missing, inconsistent, or delayed records should be documented and handled clearly.
- The dashboard is a demonstration of analytical reporting and decision support, not an official source of truth without validation.

This section shows professional judgment and public-sector awareness.

---

## Why this matters for NT Government

This project is relevant to education, planning, and service delivery roles because it shows the ability to turn public data into useful operational reporting. NT Government datasets already support attendance and enrolment analysis, and attendance remains a live issue in the Territory [web:8][web:12].

It also demonstrates the difference between making a chart and building a reporting asset that supports decision-making.

---

## Future improvements

- Add a live data refresh pipeline.
- Include more years of history for trend analysis.
- Add cohort analysis by year level or school type.
- Add annotations for intervention periods or policy changes.
- Improve accessibility and mobile readability of dashboard pages.

---

## Conclusion

This project demonstrates the ability to transform public-sector education data into clear, actionable reporting for operational and executive stakeholders. It combines data preparation, relational modeling, and dashboard design to support better attendance monitoring and earlier intervention [web:8][web:19].
