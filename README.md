# Sleep and Depression Analysis

## Overview
This project explores how sleep duration is influenced by various mental health indicators, including depression level, perceived mental health, and demographic factors. Using data from the NHANES health survey, our team applied multiple linear regression techniques to examine the relationship between sleep and depression.

## Dataset
- **Source**: NHANES (National Health and Nutrition Examination Survey)
- **Sample size**: 5,000+ survey responses
- **Variables**: Sleep duration, depression score, age, gender, mental health days, sleep trouble

## Tools Used
- **Language**: R
- **Libraries**: `dplyr`, `ggplot2`, `car`, `broom`
- **Software**: RStudio, LaTeX

## Methodology
- Performed extensive data cleaning and preprocessing
- Conducted assumption testing: linearity, normality, homoscedasticity, and multicollinearity (VIF)
- Built multiple linear regression models using both full and stepwise approaches
- Validated model using LOOCV (Leave-One-Out Cross Validation)
- Visualized residuals and regression diagnostics

## Key Results
- The final model explained approximately 6.7% of the variance in sleep duration.
- Variables such as **sleep trouble** and **gender** were statistically significant predictors.
- Residuals were approximately normal and evenly spread, validating model assumptions.

##  Files
-  [`STA302-Final_Project.pdf`](./STA302-Final_Project.pdf): Full statistical analysis and interpretation
-  [`STA302_Final_Part2_Poster.pdf`](./STA302_Final_Part2_Poster.pdf): Project poster used for public presentation

## Contributors
- **Kin Fung Ng (Rex)** – Regression modeling, data analysis, diagnostics, and final report authoring  
- **Ariane Lin** – Data cleaning, statistical validation, and report drafting  
- **Jing Jin** – Visualization, exploratory analysis, and poster design

##  Notes
This project was completed as part of the STA302 final course project at the University of Toronto, under the guidance of course instructor and TAs.

##  License
This project is for educational and portfolio purposes only. Not for commercial use.

