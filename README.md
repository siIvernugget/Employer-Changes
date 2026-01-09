# Econometrics Case Study: Employer Changes in Austria
This repository contains **Case Study 3**, a reproducible, econometric analysis, as part of a university project, investigating labor mobility in Austria between 1986 and 1998. The aim was to model how often workers change employers based on socioeconomic factors like age, gender, and income.

## Overview
* **`change.csv`**: The raw dataset containing the data for our analysis.
* **`Task Description.pdf`**: Task Description.
* **`employer changes.Rnw`**: The main file containing the R code for the analysis and LaTeX.
* **`employer changes.pdf`**: The final output file.

## The Analysis
Written in **LaTeX** with **R** integration, the project covers:
* **Regression Modeling:** OLS, quadratic terms, and interaction effects.
* **Hypothesis Testing:** F-tests for coefficient equality.
* **Model Selection:** Comparing models using AIC and BIC.
* **Diagnostics:** Testing OLS assumptions.

## How it works
To run the analysis and compile the PDF make sure to install and run the following packages:
```r
install.packages(c("tidyverse", "readxl", "knitr", "formatR", "tinytex"))
```
To compile the PDF

**Author:** Bischoy Bert
