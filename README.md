# **Exploratory Data Analysis of the NYC Public School System Before & After Covid** 

# *Examining Patterns and Trends in Student Demogrpahics, Chronic Absenteeism, and Graduation Rate Data from 2015-2023*
___

## Overview

This analysis aims to find trends and patterns among the NYC Public School student population to determine factors that may contribute to or indicate higher/lower chances chronic absenteeism and how those factors may impact overall graduation rates.

___

## Data Sources

The information was obtained from [NYC Open Data](https://opendata.cityofnewyork.us/).

Three datasets were used:
- [**2019-20 Demographic Snapshot - Citywide**](https://data.cityofnewyork.us/Education/2019-20-Demographic-Snapshot-Citywide/ycfm-qijh/about_data)
    - Student and demographic citywide data. Enrollment counts are based on the October 31st Audited Register for each school year.

    - Starts during the 2015-16 school year and ends during the 2019-20 school year

- [**2016-17 - 2020-23 Citywide End-of-Year Attendance and Chronic Absenteeism Data**](https://data.cityofnewyork.us/Education/2016-17-2020-23-Citywide-End-of-Year-Attendance-an/sgsi-66kk/about_data)
    - Overall attendance data include students in Districts 1-32 and 75 (Special Education). Students in District 79 (Alternative Schools & Programs), charter schools, home schooling, and home and hospital instruction are excluded. Pre-K data do not include NYC Early Education Centers or District Pre-K Centers; therefore, Pre-K data are limited to those who attend K-12 schools that offer Pre-K.

    - Starts during the 2018-19 school year and ends with the 2022-23 school year

-   [**Graduation results for Cohorts 2012 to 2019 (Classes of 2016 to 2023)**](https://data.cityofnewyork.us/Education/Graduation-results-for-Cohorts-2012-to-2019-Classe/mjm3-8dw8/about_data)
    - This report includes Graduation Outcomes as calculated by the New York State Education Department.

    - The cohort consists of all students who first entered 9th grade in a given school year (e.g., the Cohort of 2006 entered 9th grade in the 2006-2007 school year). Graduates are defined as those students earning either a Local or Regents diploma.

    - Covers graduating classes from the years 2016 to 2023 and students starting high school between the years of 2012 to 2019

___

## Tools

- Python
- NumPy for mathmatical & statistical operations
- Pandas for data manipulation
- Matplotlib & Seaborn for data visualization
- Jupyter Notebooks