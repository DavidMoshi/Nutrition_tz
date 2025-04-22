# Nutrition_tz
# Child Anthropometric Z-Score Analysis Using R
This project demonstrates the use of **R** and the **anthro** package to compute and categorize **child nutritional status** using **WHO growth standards**. The script calculates **Z-scores** for height-for-age (stunting) and weight-for-age (underweight), and classifies children into categories such as *Severe*, *Moderate*, *Normal*, and *Extreme*.

## Key Features
- Data import and wrangling with `rio`, `dplyr`, and `janitor`  
- Z-score computation using the `anthro` package  
- Classification of **stunting** and **underweight** based on WHO cut-offs  
- Ready for export to Excel for reporting or further analysis  

## Tools & Packages
- `anthro` – Z-score calculation based on WHO reference  
- `tidyverse` – Data manipulation and piping  
- `gt`, `gtsummary` – Table creation (optional in the script)  
- `rio` – Easy data import/export  
- `case_when()` – Logical condition mapping for nutritional categorization  

## Files
- `sample.xlsx` – Sample input dataset (child sex, age, length/height, weight)  
- `z-scores.xlsx` (optional export) – Processed Z-score output  
- `R script` – Main file containing data wrangling, analysis, and categorization
