# Scrape-ALICE-budget-data


# ALICE Household Survival Budget – Indiana (2022)

This repository contains a Python script that automates the download of ALICE (Asset Limited, Income Constrained, Employed) Household Survival Budget data for all counties in Indiana (2022).

ALICE households earn above the Federal Poverty Level but still cannot afford the basic cost of living. The Household Survival Budget estimates the bare minimum costs of housing, food, transportation, child care, health care, and technology.

## Features
Pulls ALICE survival budget data via the https://www.unitedforalice.org/api/survival-budget-calculator endpoint.

Iterates across all 92 Indiana counties.

Loops through household demographic combinations (adults, seniors, children, preschoolers, infants).

Applies constraints so the number of adults and children per household ≤ 6 each.

Compiles everything into one CSV file for analysis.

## Objective
Automate the retrieval of ALICE Household Survival Budget data for all counties in Indiana (2022) and create interactive visualizations.

## Data Source
- [United for ALICE – Survival Budget Calculator](https://www.unitedforalice.org/household-budgets/indiana)

## Visualizations
-  
- [Tableau Dashboard 1](https://public.tableau.com/views/Trial_17321231466610/Dashboard3)  
- [Tableau Dashboard – Marion County](https://public.tableau.com/views/budget_17322263694830/Dashboard1)


