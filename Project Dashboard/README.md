# HR Analytics Dashboard | Power BI

## Project Overview

The **HR Analytics Dashboard** is an interactive Power BI project designed to explore employee data and help understand workforce composition, employee attrition, job satisfaction, and experience across the organization.

The dashboard brings key HR metrics and visual analysis together in one place so that users can explore workforce patterns using demographic and organizational filters.

## Project Objectives

- Analyze the overall employee workforce.
- Understand employee attrition and the attrition rate.
- Compare employee distribution across departments and gender.
- Explore age-group and salary-slab distributions.
- Examine attrition patterns by department, gender, job role, and experience.
- Review job satisfaction and employee experience indicators.

## Tools & Technologies

- **Microsoft Power BI** – dashboard development, data modeling, and visualization.
- **CSV / Excel-compatible dataset** – employee data source.
- **Power Query** – data loading and preparation within Power BI.
- **DAX** – measures and KPI calculations.

## Dataset

The project uses the `HR_Analytics-4.csv` dataset.

| Dataset detail | Value |
|---|---:|
| Employee records | 1,480 |
| Columns | 37 |
| Attrition marked Yes | 241 |
| Attrition marked No | 1,239 |
| Calculated attrition percentage | 16.28% |

The dataset includes fields covering:

- **Employee information:** EmpID, Age, AgeGroup, Gender, MaritalStatus
- **Organization:** Department, JobRole, JobLevel, BusinessTravel
- **Compensation:** MonthlyIncome, SalarySlab, DailyRate, HourlyRate, Salary Hike %
- **Satisfaction:** EnvironmentSatisfaction, JobSatisfaction, JobInvolvement, RelationshipSatisfaction, WorkLifeBalance
- **Experience:** TotalExperience(Years), YearsatCompany, YearsinCurrentRole, YearsSincePromotion, YearsWithCurrManager
- **Attrition and work patterns:** Attrition, OverTime, NumCompaniesWorked, TrainingsLastYear

*The attrition percentage above is calculated from the supplied CSV as 241 records marked “Yes” divided by 1,480 total records. It is a dataset-level calculation and may differ if report filters are applied.*

## Dashboard Highlights

The supplied Power BI report includes the following KPI cards and visual analyses:

### Key Performance Indicators
- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate %
- Average Age
- Average Experience

### Visualizations
- Department-Wise Employee Count
- Age Group Distribution
- Attrition by Department
- Attrition by Gender
- Attrition Trend by Experience
- Job Satisfaction by Job Role
- Employee distribution by salary slab

### Interactive Analysis
The report includes slicers/filters for exploring the data by:
- Department
- Age Group
- Gender
- Salary Slab

Selecting a filter helps users examine the corresponding workforce and attrition patterns.

## Repository Structure

A suggested GitHub repository structure:

```text
HR-Analytics-Dashboard/
│
├── HR ANALYTICS.pbix
├── HR_Analytics-4.csv
├── screenshots/
│   └── dashboard-overview.png
└── README.md
```

Add your dashboard screenshot to the `screenshots` folder and keep the filename consistent with the image reference below.

## How to Use the Project

1. Clone or download this repository.
2. Open `HR ANALYTICS.pbix` using Microsoft Power BI Desktop.
3. If Power BI asks for the data source, point it to the downloaded `HR_Analytics-4.csv` file.
4. Refresh the dataset if required.
5. Use the dashboard slicers to explore employee and attrition patterns.

## Dashboard Preview

Add a screenshot of your dashboard to the repository at `screenshots/dashboard-overview.png`.

Once uploaded, you can display it here:

```markdown
![HR Analytics Dashboard](screenshots/dashboard-overview.png)
```

## Key Takeaways

This project demonstrates how HR data can be organized and explored through interactive business intelligence reporting. It focuses on workforce distribution, attrition, satisfaction, and employee experience to support data-informed HR discussions.

## Skills Demonstrated

- Data cleaning and preparation
- Exploratory data analysis
- Data modeling
- DAX measures and KPI development
- Interactive dashboard design
- Business intelligence and data storytelling

