# netflix-databricks-analytics
Netflix Content Intelligence Platform built on Databricks


Netflix Content Intelligence Platform
Built on Databricks Free Edition using PySpark, SQL, and Python

Author: Tanusha Mukund

Overview

The Netflix Content Intelligence Platform is an end-to-end data engineering and analytics project developed entirely using Databricks Free Edition.

It showcases the full lifecycle of modern data workflows:

Data ingestion using Databricks serverless compute

Cleaning and standardization of messy date formats

Feature engineering for deeper insights

Exploratory analysis using Spark SQL

Interactive visualizations using Pandas, Seaborn, Matplotlib

A simple AI-style natural language query engine

Saving processed data back into Databricks tables

This project demonstrates strong skills in data engineering, analytics, PySpark, and Databricks platform usage — ideal for roles in Data Analytics, Data Engineering, and ML Ops foundations.

Key Features
1. Data Pipeline & Cleaning

Loaded dataset directly from Databricks table

Standardized inconsistent date formats (multiple patterns: "MMMM d, yyyy", "MMMM yyyy", "yyyy")

Removed malformed values

Created clean columns:

release_year

release_decade

content_age_years

is_recent

2. Exploratory Data Analysis (Spark SQL)
- Top content-producing countries
- Movie vs. TV Show distribution
- Cleaned category/genre ranking
- Content trends across decades

All analysis is done using serverless Spark SQL.

3. Visualizations

Interactive and publication-quality plots using:

Matplotlib

Seaborn

Pandas

Visuals include:

Top ratings

Top countries

Category popularity

Trend analysis

4. AI-Style Natural Language Query Engine

Simple natural-language analytics queries like:

"How many movies?"
"How many TV shows?"
"Show latest titles"
"Show oldest titles"


This converts user queries → Spark logic.

5.Processed Output Stored Back to Databricks

Final cleaned data is written back as a reusable Delta table:

workspace.default.netflix_processed

Technologies Used
Layer	Technology
Compute	Databricks Free Edition (serverless)
Languages	Python, SQL
Processing	PySpark (Spark SQL + DataFrame API)
Visualization	Pandas, Matplotlib, Seaborn
Storage	Delta Tables on Databricks
Notebook	Databricks Collaborative Workspace
📁 Project Structure
├── Netflix_Content_Analytics.ipynb   # Main Databricks Notebook
├── README.md                         # Project documentation (this file)
└── /visuals                          # (Optional) Exported images


Sample Insights Generated

United States and India are the largest content producers

Movies dominate the catalog compared to TV Shows

Most content is rated TV-MA, TV-14, or PG-13

Significant growth in the 2010s and 2020s

International content categories are becoming increasingly common

📝 Summary Metrics

Includes an automatically generated summary:

Total titles

Number of countries represented

Number of unique category types

Range of release years

Average content age
