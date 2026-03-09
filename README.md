# BUS 32120 Final Project  
## China Silver Economy: A Screening Analysis of Caregiver Training and Dispatch Opportunity

**Team Members:** Jeremy Ye, Lawrence Li  
**Course:** BUS 32120  
**Quarter:** Winter 2026  

## Project Overview

This project studies whether China’s aging population and elder-care labor pressure are consistent with a potential business opportunity in caregiver training and dispatch.

The target audience is founders or small investors evaluating a caregiver training and staffing business in China.

Our analysis uses both **Python** and **SQL**.  
Python is used for data cleaning, feature engineering, exploratory analysis, visualization, and modeling.  
SQL is used to organize and compare the data through grouped queries, joins, subqueries, and window functions.

## Main Research Question

Does China show enough aging-related demand growth and labor-supply pressure to justify deeper evaluation of a caregiver training and dispatch startup?

## Datasets

This project uses two main datasets:

1. **World Bank indicators**
   - China, Japan, and South Korea
   - Variables include:
     - population ages 65+ (%)
     - population ages 65+ (total)
     - nurses and midwives per 1,000 people
     - total population
     - GDP per capita

2. **China elder-care operations data**
   - Annual China-only dataset for 2019–2024
   - Variables include:
     - 65+ population
     - 65+ population share
     - elder-care institutions
     - elder-care beds
     - registered nurses

## Files in This Repository

- `final_python_notebook.ipynb`  
  Main polished notebook for the final project. Includes introduction, data quality checks, feature engineering, tables, charts, models, and conclusion.

- `final_sql_notebook.ipynb`  
  SQL notebook containing the required SQL queries for the project, including joins, window functions, group by queries, and subqueries.

- `data/wb_macro.csv`  
  Cleaned country-year macro dataset used in both Python and SQL analysis.

- `data/country_dim.csv`  
  Small country dimension table used in SQL joins.

- `data/china_ops.csv`  
  China elder-care operations dataset used in both Python and SQL analysis.

- `final_project.sqlite`  
  Local SQLite database file used for SQL analysis.

## Methods

### Python
- Data cleaning and quality checks
- Feature engineering
- Aggregated summary tables
- Line charts for aging, nurse supply, labor pressure, and elder-care bed capacity
- Two models:
  - Linear Regression
  - Logistic Regression

### SQL
- Grouped summaries
- Joins
- Window functions
- Subqueries
- China vs. benchmark comparisons

## Main Takeaway

The results do not prove that a startup in caregiver training and dispatch will succeed.  
However, they suggest that China’s aging demand and labor-side pressure are strong enough to justify deeper business due diligence.

## AI Use Disclosure

We used generative AI tools to support brainstorming, code debugging, wording improvement, and project organization.  
All analysis decisions, final interpretations, and submitted work were reviewed and edited by the team.
