# HR Attrition Analysis & Dashboard

## Project Overview

This project focuses on analyzing employee attrition using Microsoft Excel, PivotTables, Power Pivot, and interactive dashboards.

The objective is to understand employee attrition patterns across departments and genders, and explore how employee satisfaction, performance, overtime, and years at the company relate to workforce trends.

The project includes data preparation, data modeling, DAX calculations, and an interactive HR dashboard to present insights in a simple and visual way.

## Objectives

* Analyze employee attrition across different departments.
* Compare employee attrition by gender.
* Calculate attrition rates and overtime rates.
* Analyze employee satisfaction and performance ratings.
* Understand the relationship between employee experience and attrition.
* Build an interactive dashboard using Excel PivotTables, PivotCharts, and Slicers.

## Tools & Technologies

* **Microsoft Excel**
* **Power Query / Excel Data Preparation**
* **Power Pivot**
* **DAX (Data Analysis Expressions)**
* **PivotTables**
* **PivotCharts**
* **Slicers**
* **Data Modeling**

## Dataset

The project uses an HR employee dataset containing information related to:

* Employee details
* Department
* Gender
* Job role
* Age
* Salary
* Attrition status
* Overtime
* Years at company
* Job satisfaction
* Work-life balance
* Job involvement
* Environment satisfaction
* Performance rating

The data is organized into fact and dimension tables to support analysis using Power Pivot.

## Data Model

The workbook follows a structured data model consisting of:

### Fact Table

**Fact_Attrition**

Contains employee attrition-related records, including:

* Attrition ID
* Employee ID
* Date ID
* Attrition status
* Monthly income
* Overtime
* Years at company
* Years since last promotion
* Job satisfaction

### Dimension Tables

**Dim_Employee**

Contains employee information such as department, gender, job role, age, education, and salary.

**Dim_Satisfaction**

Contains work-life balance, job involvement, environment satisfaction, and relationship satisfaction.

**Dim_Performance**

Contains performance ratings, promotion information, and manager feedback.

**Dim_Date**

Contains date, month, quarter, year, and day of the week.

## Dashboard Features

The HR Attrition Dashboard provides interactive analysis through:

### 1. Gender Attrition Analysis

A pie chart showing employee distribution by gender.

### 2. Attrition by Department

A column chart comparing employee attrition across departments.

### 3. Attrition and Overtime Analysis

A comparison of attrition count, attrition rate, and overtime rate by department.

### 4. Employee Satisfaction Analysis

Analysis of average work-life balance, job involvement, and environment satisfaction across departments.

### 5. Performance and Experience Analysis

Comparison of average performance rating and average years at company across departments.

### 6. Interactive Department Slicer

A Department slicer allows users to filter the dashboard and explore department-specific information.

## Key Skills Demonstrated

* Cleaning and organizing HR data.
* Working with fact and dimension tables.
* Building relationships in Power Pivot.
* Creating calculated measures using DAX.
* Creating PivotTables and PivotCharts.
* Designing an interactive Excel dashboard.
* Analyzing HR metrics and identifying workforce patterns.
* Presenting data-driven insights through visualizations.

## Project Structure

```text
HR-Attrition-Analysis/
│
├── HR_Attrition_Analysis.xlsx
│
└── README.md
```

## How to Use

1. Download or clone this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Navigate to the Dashboard sheet.
4. Use the Department slicer to filter the charts.
5. Explore attrition, satisfaction, overtime, and performance metrics.

**Note:** Microsoft Excel with Power Pivot support is recommended for exploring the data model and DAX measures.

## Conclusion

This project demonstrates how Excel, Power Pivot, and DAX can be used to transform HR data into an interactive dashboard. It provides practical experience in data modeling, business analytics, and data visualization while exploring employee attrition and workforce-related metrics.

## Author

**Sanskar Gadhe**

B.Tech Electronics and Communication Engineering Student

Interested in Data Analytics, Business Intelligence, and Data Visualization.
