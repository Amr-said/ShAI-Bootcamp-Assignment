# Employee Compensation Analysis

## Overview
This project analyzes a dataset containing information about employee compensation within an organization. The dataset includes details such as salaries, job titles, and departmental information. The analysis covers basic data exploration, descriptive statistics, data cleaning, visualizations, grouped analysis, and correlation analysis.

## Table of Contents
- [Employee Compensation Analysis](#employee-compensation-analysis)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [About Dataset](#about-dataset)
  - [Features](#features)
  - [Tasks](#tasks)
  - [Analysis Highlights](#analysis-highlights)
    - [Data Exploration](#data-exploration)
    - [Descriptive Statistics](#descriptive-statistics)
    - [Data Cleaning](#data-cleaning)
    - [Data Visualization](#data-visualization)
    - [Grouped Analysis](#grouped-analysis)
    - [Correlation Analysis](#correlation-analysis)
  - [License](#license)

## About Dataset
The salaries dataset provides comprehensive information about employees' compensation, job titles, and related details within the organization. Key features include 'Id', 'EmployeeName', 'JobTitle', 'BasePay', 'OvertimePay', 'OtherPay', 'Benefits', 'TotalPay', 'TotalPayBenefits', 'Year', 'Notes', 'Agency', and 'Status'.

## Features
- 'Id'
- 'EmployeeName'
- 'JobTitle'
- 'BasePay'
- 'OvertimePay'
- 'OtherPay'
- 'Benefits'
- 'TotalPay' (salary)
- 'TotalPayBenefits'
- 'Year'
- 'Notes'
- 'Agency'
- 'Status'

## Tasks
1. **Basic Data Exploration**: Identify the number of rows and columns, data types, and missing values.
2. **Descriptive Statistics**: Calculate mean, median, mode, range, and standard deviation of salaries.
3. **Data Cleaning**: Handle missing values and clean the dataset.
4. **Basic Data Visualization**: Create histograms and pie charts to visualize salary distributions and departmental proportions.
5. **Grouped Analysis**: Compare average salaries across different job titles and years.
6. **Simple Correlation Analysis**: Identify correlations between salary and other numerical columns.



## Analysis Highlights
### Data Exploration
- Detailed exploration of the dataset, including shape, data types, and missing values.


### Descriptive Statistics
- Insights into salary distributions, key statistics, and range of salaries.


### Data Cleaning
- Handling missing values in 'BasePay' and 'Benefits' columns.
- 

### Data Visualization
- Utilizing histograms, pie charts, and box plots to visualize data.

[Salaries Distripution] <img src="./imgs/newplot (6).png">
[Employees Proportion in each Jop Title] <img src="./imgs/newplot (7).png">


### Grouped Analysis

[Average Salaries for Top 11 Job Titles Across Different Years]<img src="./imgs/newplot (9).png">
[# Range of salaries for the top 11 job titles]<img src="./imgs/newplot (10).png">
[# Range of Salaries for 2011, 2012, 2013, 2014]<img src="./imgs/newplot (11).png"> <img src="./imgs/newplot (13).png"> <img src="./imgs/newplot (14).png"> <img src="./imgs/newplot (15).png">

### Correlation Analysis
- Identifying correlations and visualizing the relationship between 'TotalPay' and 'TotalPayBenefits'.

[# correlation heatmap for numeric features in the dataset]<img src="./imgs/download (3).png">
[# Scatter plot to visualize the relationship between 'TotalPay' and  TotalPayBenefits']<img src="./imgs/newplot (12).png">

## License
This project is licensed under the [MIT License](LICENSE).
