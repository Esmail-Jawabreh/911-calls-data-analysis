# 911 Calls Data Analysis (Montgomery County, PA)

## Overview
This project performs an exploratory data analysis (EDA) of 911 emergency calls in Montgomery County, PA.  
The goal is to uncover temporal patterns, common incident reasons, busiest locations, and workload trends using Python data analysis and visualization techniques.

## Dataset
- **Source:** [Kaggle – 911 Calls: Montgomery County, PA](https://www.kaggle.com/mchirico/montcoalert)  
- **File:** `911.csv`  
- **Description:** Each row represents a 911 call with:
  - Timestamp
  - Location details (latitude, longitude, ZIP code, township)
  - Title field (containing the reason for the call: EMS, Fire, or Traffic)

## Objectives
1. Parse datetime and analyze calls by **hour, day, and month**.
2. Extract **Reason** (EMS / Fire / Traffic) from the `title` field and compare volumes.
3. Identify **top ZIP codes** and **top Townships** with the highest call frequency.
4. Find **busiest hours/days** and monthly trends.
5. Visualize key insights with clear and descriptive plots.

## Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Example Insights
- EMS is the most common reason for calls.
- Peak call hours occur during midday and evening.
- Certain ZIP codes and townships have consistently high call volumes.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/911-calls-data-analysis.git
   cd 911-calls-data-analysis
