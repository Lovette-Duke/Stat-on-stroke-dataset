
Statistical Concepts Analysis:
This repository contains R code for conducting statistical analysis on a healthcare dataset related to strokes. The analysis covers various statistical tests and models to explore relationships between different features and the occurrence of strokes.

Dataset:
The dataset used in this analysis is sourced from healthcare-dataset-stroke-data.csv.

Setup:

Libraries: The necessary libraries for the analysis are loaded, including tidyverse and ggplot2.
Data Loading: The dataset is read into R for further analysis.
Data Preprocessing
Removing Columns: The 'id' column is dropped from the dataset.
Converting Datatypes: Datatypes are converted as necessary, including converting character columns to factors and ensuring numeric variables are appropriately typed.
Handling Missing Values: Missing values are identified and removed from the dataset.
Exploratory Data Analysis (EDA)
Statistical Summaries: Summary statistics are generated to understand the distribution of variables in the dataset.
Density Plots: Density plots are created to visualize the distribution of 'age' and 'avg_glucose_level' variables.
Modeling
Logistic Regression: Logistic regression models are fitted to predict strokes based on 'age', 'bmi', and 'avg_glucose_level'.
Chi-Squared Test: Chi-squared tests are conducted to explore the relationship between strokes and categorical variables like 'hypertension' and 'heart_disease'.
T-Test: A t-test is performed to examine the mean age of the population.
Analysis of Variance (ANOVA): ANOVA tests are conducted to analyze the impact of 'smoking_status', 'hypertension', and 'heart_disease' on age.
Spearman's Correlation Test: A correlation test is conducted to assess the relationship between 'avg_glucose_level' and 'bmi'.
Conclusion
The analysis provides insights into the factors associated with strokes, including age, hypertension, and heart disease.
Certain variables like 'age' and 'smoking_status' show significant associations with strokes, as indicated by various statistical tests.
