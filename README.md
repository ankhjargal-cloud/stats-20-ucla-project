# The Westwood Effect: Analyzing Theft Patterns

**Stats 20, Fall 2025** | **Author:** Anka Amarbayasgalan

## Overview
This project investigates a core research question: *Can we quantify the difference in theft risk between commercial zones and student-heavy residential areas?* 

Analyzing roughly 40,000 localized crime records from the Los Angeles Open Data Portal (2020–Present), this analysis explores how geographic zoning in the Westwood neighborhood dictates unique property crime risk profiles.

## Tools & Methodology
* **Language:** R
* **Libraries:** `dplyr` (data manipulation), `ggplot2` (visualization)
* **Techniques:** Data transformation, categorical grouping, stacked/grouped bar charts, logistic regression modeling, odds ratio analysis

## The Dataset
The dataset was sourced from the LA Open Data Portal and filtered specifically for the Westwood area. This isolated 39,987 relevant records. Crimes were categorized into 7 distinct theft types (e.g., Auto Theft, Burglary, Petty Theft) across 4 geographic zones (Commercial/Village, Residential, University/Student, Public/Street).

## Key Findings
1. **Commercial Dominance:** The Commercial/Village zone accounts for the largest overall volume of theft, overwhelmingly driven by Shoplifting/Commercial theft. 
2. **Zonal Vulnerabilities:** While Residential areas experience fewer total crimes, they face a disproportionately higher risk of Residential/Commercial Burglaries and Thefts from Vehicles. Public/Street zones are the primary hotspots for Auto Theft.
3. **The University Paradox:** Logistic regression revealed that despite a lower absolute volume of crime, the odds of a theft being a burglary in the University/Student zone are **2.57 times higher** than in the Commercial zone.
