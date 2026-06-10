# Managing-Salaries

A data analysis project for exploring and managing San Francisco public employee salary data.

## Overview

This project analyzes salary information for San Francisco employees across various city departments and agencies. It uses Python's pandas library to load, clean, and explore salary datasets containing detailed compensation information.

## Project Contents

- **Salaries_Exercise.ipynb** - A Jupyter notebook containing data analysis exercises that explore salary trends in the SF Bay Area

## Dataset

The project uses the `Salaries.csv` file which contains approximately **148,654 records** of employee salary data with the following columns:

| Column | Description |
|--------|-------------|
| **Id** | Unique employee identifier |
| **EmployeeName** | Full name of the employee |
| **JobTitle** | Position/role title |
| **BasePay** | Base salary amount |
| **OvertimePay** | Additional overtime compensation |
| **OtherPay** | Miscellaneous additional pay |
| **Benefits** | Benefits package value |
| **TotalPay** | Sum of base, overtime, and other pay |
| **TotalPayBenefits** | Total compensation including benefits |
| **Year** | Year of the record |
| **Agency** | City department/agency |

## Key Findings

Through the analysis, the notebook explores:

- **Average Base Pay**: ~$66,325
- **Maximum Overtime Pay**: $245,131.88
- Individual employee salary breakdowns
- Department-level salary comparisons
- Year-over-year salary trends

## How to Use

1. Open `Salaries_Exercise.ipynb` in Jupyter Notebook or Google Colab
2. Execute cells sequentially to:
   - Load and inspect the salary data
   - Perform data cleaning operations
   - Query specific employee information
   - Analyze compensation patterns

## Data Processing

The notebook includes data cleaning steps such as:
- Converting string columns to numeric types
- Removing columns with mostly null values (Notes, Status)
- Handling mixed data types in salary columns

## Technologies

- **Python 3**
- **Pandas** - Data manipulation and analysis
- **Jupyter Notebook** - Interactive code environment

## Purpose

This project serves as an educational resource for:
- Learning pandas data analysis techniques
- Understanding public sector compensation structures
- Practicing data exploration and querying
- Analyzing real-world government salary datasets
