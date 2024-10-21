# R Exploratory Data Analysis
## Project Overview
This project demonstrates the process of exploratory data analysis (EDA) using R on a dataset named solar.csv. The analysis covers key tasks such as data cleaning, handling missing values, feature selection, data transformation, and basic visualizations to prepare the dataset for further analysis or predictive modeling.

## Project Structure
RMarkdown File: Exploring Data.Rmd – This file contains all code and explanations related to the exploratory data analysis process.

## Key Tasks
###   Data Loading:
  The dataset solar.csv is loaded, and an initial inspection of its structure and summary statistics is performed.
###   Handling Missing Data:
  Missing values in the pressure variable are imputed using the mean.
  Missing values in the snowing variable are assumed to be "No" and corrected accordingly.
###   Feature Selection:
  Irrelevant features such as Continent (constant value) and ID (unique values) are removed as they do not contribute to predictive modeling.
###   Data Cleaning:
  Categorical variables (smart) are cleaned, with values like "y/n" converted to "Yes/No."
  Character data, such as latitude, are transformed into a numerical format using custom R functions.
###   Data Visualization:
  Basic visualizations, including histograms and bar plots, are created using ggplot2 to explore the distribution and relationships between variables.

## Key Skills Demonstrated
### Data Cleaning: Identifying and handling missing values and irrelevant features.
### Feature Engineering: Transforming and preparing data for modeling.
### Data Visualization: Using ggplot2 for exploratory visualizations.

Libraries Used:
-caret
-dplyr
-ggplot2
-stringr
-corrplot
-Hmisc

## Insights
The analysis explores the data in detail, handling missing values, cleaning variables, and preparing features, making the dataset ready for further machine learning tasks.

