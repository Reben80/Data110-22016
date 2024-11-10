### Week 10: Analysis of Daily Arrests in Montgomery County


#### Project Overview

- **Objective**: This week, we focused on selecting, importing, and analyzing a dataset about daily arrests in Montgomery County. The goal was to practice data cleaning, analysis, and visualization techniques to derive insights.
- **Dataset Information**: [dataMontgomery](https://data.montgomerycountymd.gov) - Daily Arrests (Dataset used: 'Daily_Arrests_20241001 (1).csv')
- [Google Colab](Week10_In_Class.ipynb) 

#### Key Steps Covered

1. **Dataset Import**:
   - Imported the dataset and integrated it into the Python environment.

2. **Initial Data Exploration**:
   - Explored the dataset to understand features and data quality.

3. **Data Cleaning**:
   - Cleaned the dataset by handling missing values, removing duplicates, and formatting columns.

4. **Data Analysis**:
   - Conducted exploratory data analysis (EDA) to understand trends and patterns.
   - Created visualizations to explore arrest trends and demographics.

5. **Discussion and Findings**:
   - Interpreted the analysis outcomes to derive insights about arrest patterns.

#### Next Steps

- Continue with more advanced data visualization techniques (Geospatial Heatmap).

-----------

# Week 10 Assinment 

 Assignment: Analyzing Theft-Related Data

## Overview
In this assignment, you will explore theft-related offenses in the dataset provided. Your goal is to identify patterns, visualize the data, and draw meaningful insights from theft-related incidents.

### Objectives
- Filter the dataset to focus on theft-related offenses.
- Analyze the characteristics of theft incidents, such as time, location, and age.
- Create meaningful visualizations to present your findings.



### Steps

1. **Filter Theft-Related Offenses**
   - Filter the dataset to include only rows where the `OFFENSE` column contains the word "theft".
   - Create a new DataFrame called `theft_df` for this filtered data.
 

2. **Exploratory Data Analysis (EDA)**
   
   - **Task**: Answer the following questions:
     - What is the total number of theft incidents?
     - What is the range of ages involved in theft offenses?

3. **Visualizing Theft Offenses by Day of the Week**
  
    
   - **Task**: Which day of the week has the highest number of theft arrests? What might be the reasons for this trend?

4. **Age Distribution of Theft Offenders**
   
 
   - **Task**: Describe the age distribution. Which age group seems to be most involved in theft offenses?

 

5. **Offense Analysis**
   - Analyze the types of theft offenses.
   - **Task**: Use `value_counts()` on the `OFFENSE` column to find out what kinds of theft are most common. Create a bar chart to visualize this.

6. Can you make some other visualizaion related to theft offenses? 
