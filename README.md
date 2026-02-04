# CIST 2500: Applied Statistics Semester Project

## Overview

This repository contains my semester project for CIST 2500. The project applies statistical methods learned in the corse to real-world datasets. I used Jupyter Notebook with Python to perform the same statistical analyses that were taught using Excel in class.

## View Project

Click on the file Mujica_-_Semester_Project.ipynb

## Repository Contents

### Datasets

- `Movies_2016_2.csv` - Movie performance data (2016)
- `Movies_2016_2b.csv` - Superhero movies subset
- `Movies_2016_3.csv` - Extended movie dataset
- `Reaction_Typing_10.csv` - Student reaction time and typing speed data
- `Reaction_Typing_11.csv` - Extended reaction/typing data with submission timing
- `Student_Winter_Attitudes_12.csv` - Student attitudes toward winter by class level
- `Types_of_MnMs_13.csv` - M&M candy counts by type
- `Types_of_MnMs_13b.csv` - M&M data formatted for regression analysis

### Analysis Files

- `Mujica_-_Semester_Project.ipynb` - Main Jupyter Notebook with all analyses
- `Mujica_-_Semester_Project.pdf` - PDF export of the notebook
- `Mujica_-_Semester_Project.docx` - Word document version
- `Project_Instructions.pdf` - Original project requirements

## Statistical Methods Implemented

### Chapter 2: Descriptive Statistics - Tabular and Graphical Displays
- Pivot tables and cross-tabulations
- Scatter plots with annotations
- Data visualization using matplotlib

### Chapter 3: Descriptive Statistics - Numerical Measures
- Measures of central tendency (mean, median, mode)
- Measures of variability (variance, standard deviation, IQR)
- Outlier detection (IQR method and Empirical Rule)
- Correlation analysis
- Box plots
- Trend line fitting

### Chapter 10: Inference About Means and Proportions with Two Populations
- Two-sample t-tests (unequal variances)
- Paired t-tests
- Confidence intervals for difference in means
- Hypothesis testing for proportions
- Margin of error calculations

### Chapter 11: Inferences About Population Variances
- F-tests for equality of variances
- Chi-square tests for variance
- Confidence intervals for standard deviation
- Comparative variance analysis by groups

### Chapter 12: Tests of Goodness of Fit, Independence, and Multiple Proportions
- Chi-square test of independence
- Contingency table analysis
- Marascuilo pairwise comparison procedure
- Expected frequency calculations

### Chapter 13: Experimental Design and Analysis of Variance
- One-way ANOVA
- Fisher's Least Significant Difference (LSD) test
- Bonferroni correction
- Profile plots with error bars
- Simple linear regression
- OLS (Ordinary Least Squares) regression

## Key Findings

### Movie Analysis
- Strong positive correlation (r = 0.918) between opening weekend and total gross sales
- Opening gross sales positively correlated with number of theaters (r = 0.630)
- Weeks in release moderately correlated with total sales (r = 0.474)

### Reaction Time Study
- No significant difference in typing speed between early and late submissions (p = 0.228)
- Significant improvement in reaction times from first to second attempt (p = 0.011)
- Higher variance in reaction times for early submitters compared to late submitters

### Winter Attitudes Survey
- Significant relationship between class standing and winter attitudes (χ² = 6.43, p = 0.04)
- Junior students predominantly hold "meh" attitudes toward winter
- Senior students show more positive (love) attitudes

### M&M Analysis
- Significant differences in candy counts across M&M types (F = 12.29, p < 0.001)
- Peanut M&Ms contain fewer candies per bag (M = 12.84) than Regular (M = 15.36) or PB (M = 15.40)
- Peanut M&Ms have significantly more blue candies (M = 5.08) than Regular (M = 2.40) or PB (M = 1.72)
- Weak negative relationship between total candies and blue candies (R² = 0.081)

## Technologies Used

### Python Libraries
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical graphics
- **scipy** - Scientific computing and statistical tests
- **statsmodels** - Statistical modeling and hypothesis testing

### Development Environment
- Jupyter Notebook
- Python

## Project Reflection

### Learning Outcomes

Through this project, I gained hands-on experience with:
- Python-based statistical analysis workflows
- Converting Excel-based analyses to code
- Data cleaning and preparation in pandas
- Creating publication-quality visualizations
- Interpreting complex statistical outputs
- Writing reproducible research code

## Academic Integrity Notice

This project is submitted as academic work for CIST 2500. Please do not copy or reproduce for academic submissions.
