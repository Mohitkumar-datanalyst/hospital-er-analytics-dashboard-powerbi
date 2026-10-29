# hospital-er-analytics-dashboard-powerbi
Power BI Hospital Emergency Room Analytics Dashboard analyzing patient admissions, waiting times, satisfaction scores, referral patterns, and operational KPIs through interactive data visualization.


# Hospital Emergency Room Analytics Dashboard – Power BI

An interactive healthcare analytics solution built with Microsoft Power BI to analyze emergency room patient flow, admission outcomes, waiting times, patient satisfaction, and referral patterns using data modeling, DAX, Power Query, and data visualization.

---

## Project Overview

This project presents a Hospital Emergency Room (ER) Analytics Dashboard designed to transform healthcare operational data into meaningful insights. It helps users explore patient volumes, admission status, waiting-time performance, satisfaction scores, and department referrals through interactive reports.

The dashboard includes three report pages: Monthly View, Consolidated View, and Patient Details. It demonstrates practical applications of Power BI dashboard development, KPI reporting, healthcare data analytics, and business intelligence.

## Business Problem Statement

Emergency departments need to monitor patient demand, manage waiting times, understand admission patterns, and evaluate service experience. Without consolidated reporting, identifying operational bottlenecks and monitoring performance can be difficult.

The objective of this project is to organize emergency room data into an interactive analytical dashboard that supports operational monitoring and evidence-based decision-making.

## Dataset Description

- **Source:** Hospital emergency room practice dataset
- **Format:** CSV
- **Records:** 9,216 rows in the supplied dataset
- **Period:** April 2023 – October 2024
- **Key fields:** Admission date, patient age, gender, race, department referral, admission status, satisfaction score, waiting time, and patient count.

**Dataset:** [Download the approved, de-identified dataset](Dataset/Hospital_ER_Data_Anonymized.csv)

*Privacy note: The public dataset must be appropriately de-identified and approved for sharing. Do not publish patient names, patient IDs, or other identifying information.*

## Business Questions

- How many patients visited the emergency department during a selected period?
- What proportion of patients were admitted versus not admitted?
- What was the average patient waiting time?
- How did patient satisfaction scores vary over time?
- How many patients were seen within the 30-minute target?
- Which departments received the most referrals?
- How did patient volume vary by day of the week and hour?
- How were patients distributed across age groups, gender, and race?

## Key KPIs

- **Total Patients:** Number of patient records in the selected reporting period.
- **Average Wait Time:** Average recorded patient waiting time, in minutes.
- **Patient Satisfaction Score:** Average available satisfaction score.
- **Patients Referred:** Number of patients referred to a department.
- **Admission Rate:** Percentage of patients admitted.
- **30-Minute Target Performance:** Percentage of patients seen within the defined target.
- **Patient Volume Trends:** Distribution by month, weekday, and hour.

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query for data preparation and transformation
- DAX for measures and KPI calculations
- Microsoft Excel / CSV for source data
- Interactive data visualization and dashboard design
- Healthcare operations and performance analytics

## Project Workflow

1. **Data Understanding:** Reviewed the dataset, fields, reporting period, and operational requirements.
2. **Data Preparation:** Used Power Query to inspect data types, missing values, and inconsistencies.
3. **Data Modeling:** Prepared the analytical structure required for reporting and KPI calculations.
4. **DAX & KPI Development:** Built measures for patient counts, waiting times, satisfaction, referrals, and admission outcomes.
5. **Dashboard Development:** Created monthly and consolidated reporting views, with a patient details page.
6. **Interactive Analysis:** Added date filtering, navigation, charts, KPI cards, and demographic breakdowns.
7. **Validation:** Checked totals, filters, calculations, and visual consistency against the underlying dataset.

## Dashboard Preview

### Monthly View
![Hospital ER Monthly Dashboard](Dashboard/Hospital_ER_Dashboard.png)

*Replace this image with your actual dashboard screenshot.*

### Dashboard Walkthrough
[Watch the dashboard walkthrough](Dashboard/Hospital_ER_Dashboard_Walkthrough.mp4)

The walkthrough demonstrates the dashboard navigation, monthly reporting, consolidated analysis, and interactive filtering.

## Key Insights

The supplied dashboard displays the following examples:

- The February 2024 monthly view reports **431 patients**, an average waiting time of **36.7 minutes**, an average satisfaction score of **4.72**, and **179 referred patients**.
- The same monthly view shows approximately **65.66%** of patients within the displayed 30-minute target and **34.34%** missing it.
- In the displayed consolidated view, the report shows **6,561 patients**, an average waiting time of **35.3 minutes**, and an average satisfaction score of **4.99** for its selected date range.

These figures are specific to the displayed report filters. They should not be interpreted as results for the entire dataset without validating the reporting period and measure definitions.

## Business Impact

This dashboard demonstrates how healthcare operations data can be used to:

- Monitor patient flow and admission outcomes.
- Identify periods with higher patient demand.
- Track waiting-time performance against operational targets.
- Review patient satisfaction and department referral patterns.
- Support resource planning and service improvement discussions.

The dashboard supports operational analysis; it does not establish clinical causes or prove that any single factor causes patient outcomes.

## How to Use This Repository

- **1.** Download the approved dataset and Power BI file.
- **2.** Open the `.pbix` file in Power BI Desktop.
- **3.** Update the data source path if required.
- **4.** Refresh the data and verify the KPI calculations.
- **5.** Explore the Monthly View, Consolidated View, and Patient Details pages.

## Future Improvements

- Add peak-hour demand analysis and more detailed waiting-time trends.
- Introduce service-level KPI comparisons by department.
- Improve data quality monitoring and missing-value reporting.
- Add additional time-intelligence measures and period-over-period comparisons.
- Publish a secure Power BI Service version where appropriate.

## About the Author

**Mohit Kumar**  
Data Analyst | Power BI | DAX | SQL | Advanced Excel | Business Intelligence

Interested in Data Analyst, Power BI Analyst, BI Developer, and freelance dashboard development opportunities.

- **GitHub:** [Explore my projects](https://github.com/your-username)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/mohitdataanalyst/)

---

**Conclusion:** This Hospital ER Analytics Dashboard demonstrates how Power BI, data modeling, DAX, and interactive visualization can turn healthcare operational data into actionable insights that support better patient-flow monitoring, service evaluation, and data-driven decision-making.
