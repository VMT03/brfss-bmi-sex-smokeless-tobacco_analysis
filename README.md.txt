# BRFSS Smokeless Tobacco Analysis

## Overview

This project investigates whether smokeless tobacco use is associated with Body Mass Index (BMI) among adults living in West Virginia using data from the 2013 Behavioral Risk Factor Surveillance System (BRFSS).

The project was completed in **R** using exploratory data analysis, data cleaning, visualisation and inferential statistical methods.

---

## Research Questions

1. Is there an association between smokeless tobacco use and Body Mass Index (BMI) among adults in West Virginia?

2. Is there an association between participant sex and smokeless tobacco use in West Virginia?

---

## Dataset

**Behavioral Risk Factor Surveillance System (BRFSS) 2013**

The BRFSS is a nationwide health surveillance survey conducted annually by the Centers for Disease Control and Prevention (CDC). It collects information on health-related behaviours, chronic diseases and preventive health practices among adults in the United States.

For this analysis, only participants from **West Virginia** were included.

---

## Variables

The analysis focuses on three variables:

- `usenow3` – Current smokeless tobacco use
- `X_bmi5` – Body Mass Index (BMI)
- `sex` – Participant sex

---

## Methods

The project includes:

- Data cleaning
- Missing value handling
- Variable recoding
- Descriptive statistics
- Exploratory data analysis
- Data visualisation using **ggplot2**
- Independent two-sample t-test
- Chi-square test of independence
- Linear regression

---

## R Packages

The following R packages were used:

- ggplot2
- dplyr
- car

---

## Main Findings

- Current smokeless tobacco users had a slightly higher BMI than non-users.
- A statistically significant association was identified between smokeless tobacco use and BMI.
- Smokeless tobacco use was substantially more common among males than females.
- Sex was identified as a potential confounding variable in the relationship between smokeless tobacco use and BMI.

---

## Repository Contents

BRFSS-Smokeless-Tobacco-Analysis.Rmd
BRFSS-Smokeless-Tobacco-Analysis.html
BRFSS-Smokeless-Tobacco-Analysis.pdf
brfss2013.RData
README.MD


---

## Data Source

Centers for Disease Control and Prevention (CDC)

Behavioral Risk Factor Surveillance System (BRFSS)

https://www.cdc.gov/brfss/

---

## Author

**Vasiliki-Maria Tzouma**

Biological Sciences