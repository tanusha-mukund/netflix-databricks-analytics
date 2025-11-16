# netflix-databricks-analytics
Netflix Content Intelligence Platform built on Databricks
Author: Tanusha Mukund

## Overview

The Netflix Content Intelligence Platform is an end-to-end data engineering and analytics project developed using Databricks Free Edition.It demonstrates a complete workflow across data cleaning, transformation, SQL analytics, visualization, and interactive querying.
This project illustrates practical experience in:
Serverless compute environments
PySpark DataFrame transformations
Spark SQL analytics
Feature engineering
Visualization with Python
Building a natural language query layer
The objective is to showcase real-world data engineering and analytics skills within a modern cloud-based workspace.

## Key Features
### 1. Data Pipeline and Cleaning

Loaded dataset from Databricks workspace table
Cleaned and standardized multiple inconsistent date formats
Removed malformed rows
Engineered new fields for analysis:
release_year
release_decade
content_age_years
is_recent

### 2. Exploratory Data Analysis (Spark SQL)

Analytical queries include:
Top content-producing countries
Distribution of Movies vs TV Shows
Cleaned category/genre analysis
Content trends across decades
All analysis is conducted using Spark SQL on serverless clusters.

### 3. Visualizations

Visualizations were created using Pandas, Seaborn, and Matplotlib, including:
Content rating distribution
Top countries by content volume
Category distributions
Trend analysis over time

### 4. Natural Language Query Engine

A simple natural-language interface maps user inputs to Spark queries.
Examples:

“How many movies?”
“How many TV shows?”
“Show latest titles”
“Show oldest titles”

### 5. Processed Output Saved Back to Databricks

The cleaned dataset is stored as a Delta table for reuse:
workspace.default.netflix_processed

### 6. Supervised ML Prediction

Random Forest was used to predict which movies would be a "Hit"

##Technologies Used

Component	Technology
Compute Platform	Databricks Free Edition
Languages	Python, SQL
Processing Engine	PySpark (Spark SQL + DataFrame API)
Visualization	Pandas, Seaborn, Matplotlib
Storage	Delta Tables
Project Structure
Netflix_Content_Analytics.ipynb     # Main notebook  
README.md                           # Project documentation  


### Example Insights

The United States and India produce the most Netflix content
Movies are more common than TV Shows in the dataset
Popular ratings include TV-MA, TV-14, and PG-13
Rapid growth observed in 2010s and 2020s
International content categories are increasingly prominent

### Summary Statistics

Automatically generated summary includes:
Total number of titles
Number of countries represented
Count of unique categories
Earliest and latest release years
Average content age

About the Developer

Tanusha Mukund
M.S. Business Analytics (UIUC)
Professional experience in Data Analytics, A/B Testing, SQL, Python, Adobe Analytics, and cloud-based data platforms.
