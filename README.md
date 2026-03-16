# UK Crime Data Exploratory Analysis

## Project Overview
This project analyses crime data across selected UK police forces to identify patterns in crime levels, crime types, and investigation outcomes. The analysis was conducted to support a real estate stakeholder in identifying locations that may be more or less desirable for property investment and residential living.

The project uses open crime data published by UK Police and focuses on comparing crime patterns across multiple police force regions over two years.

## Dataset
The dataset was obtained from the UK Police open data portal:

https://data.police.uk/data/

The analysis uses street crime datasets covering the period:**January 2024 – December 2025**

The data includes information such as:
- Police force reporting the crime
- Crime category
- Investigation outcome
- Geographic location (latitude and longitude)
- Location type (e.g. supermarket, parking area, etc.)
- Month of occurrence

Multiple CSV files were downloaded and combined into a single dataset for analysis.

## Project Objectives
The main objectives of the analysis were:

- Compare crime levels across multiple police forces
- Identify the most common crime categories
- Analyse how crime levels change over time
- Examine investigation outcomes
- Identify common environments where crimes occur
- Provide recommendations on which police forces should be investigated further

## Police Forces Analysed
The analysis focuses on the following five police forces:
- Metropolitan Police Service
- West Midlands Police
- West Yorkshire Police
- Thames Valley Police
- Surrey Police

## Data Processing
The raw datasets required several preprocessing steps before analysis could be performed. These steps included:

- Loading multiple CSV files into Python using Pandas
- Combining datasets into a single dataframe
- Handling missing values
- Removing duplicate records
- Standardising categorical variables
- Validating the final dataset structure


## Exploratory Data Analysis
Exploratory data analysis (EDA) was conducted using Python, primarily using the following libraries:

- Pandas
- Matplotlib
- Seaborn

The analysis included:

- Total crime counts by police force
- Distribution of crime types
- Monthly crime trends
- Crime outcomes analysis
- Crime location analysis
- Geographic crime distribution

## Recommendations
Based on the analysis, two police forces were identified as the most suitable candidates for further investigation:

- **Surrey Police**
- **Thames Valley Police**

These regions show substantially lower crime volumes compared with the Metropolitan Police Service and may contain areas with more favourable crime environments for residential property investment.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

Git hub : https://github.com/thadsha187-coder/Crime-analysis-project.git
