# HR Analytics Dashboard

## Project Objective

The objective of this project is to analyze workforce demographics, employee retention, and organizational trends through interactive Power BI dashboards. The solution helps HR teams monitor employee distribution, track retention rates, identify attrition patterns, and support strategic workforce planning with data-driven insights.

---

## Data Source

The dataset consists of employee-related information collected from HR systems, including:

- Employee Details
- Department Information
- Job Levels
- Hire Dates
- Employee Status
- Demographic Data
- Retention Metrics

---

## Data Ingestion & Transformation

Data was imported into Power BI and transformed using Power Query.

### Key Transformations:
- Data Cleaning
- Handling Missing Values
- Removing Duplicate Records
- Data Type Validation
- Creating Calculated Columns
- Building a Date Dimension Table
- Preparing Data for Analysis and Reporting

---

## Data Modeling

A Star Schema model was implemented to improve performance and simplify reporting.

### Fact Table
- Fact_Employees

### Dimension Tables
- Dim_Date
- Job Level
- Other Supporting HR Dimensions

### Relationships
- One-to-Many Relationships
- Optimized Data Model for Efficient Query Performance

---

## DAX Measures Created

Key measures developed using DAX include:

- Total Employees
- Active Employees
- Retention Rate
- Attrition Rate
- Employee Count by Department
- Employee Count by Job Level
- Average Employee Age
- Average Employee Tenure
- Hiring Trend Metrics
- Workforce Growth Metrics

---

## Dashboard Pages

### Workforce Analysis Page

Provides a comprehensive overview of the organization's workforce.

#### Key Insights:
- Total Employee Count
- Gender Distribution
- Department-wise Employee Analysis
- Job Level Distribution
- Age Group Analysis
- Workforce Demographics
- Employee Distribution Trends

---

### Retention Rate Analysis Page

Focused on monitoring employee retention and turnover.

#### Key Insights:
- Retention Rate
- Attrition Rate
- Employee Turnover Analysis
- Hiring vs Attrition Trends
- Retention Performance Over Time
- Workforce Stability Metrics

---

## Visualizations Used

- KPI Cards
- Donut Charts
- Clustered Bar Charts
- Column Charts
- Line Charts
- Stacked Bar Charts
- Slicers
- Tables
- Interactive Filters

---

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling

---

## Business Impact

This dashboard enables HR teams and management to monitor workforce performance, improve employee retention strategies, analyze workforce demographics, and make informed business decisions through interactive and data-driven reporting.
