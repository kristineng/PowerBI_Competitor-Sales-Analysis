# PowerBI - Competitor Sales Analysis

## Overview
This project focuses on building a competitor sales analysis dashboard in Power BI using a fictional manufacturing company called Sintec and its competitors.

### Aim: The report analyzes:
- Sales performance
- Revenue trends
- Market share
- Product growth
- Geographic performance
- Competitor comparison

## Skills
- Data Cleaning
- ETL (Extract, Transform, Load)
- Data Modeling
- DAX Calculations
- Data Visualization
- Dashboard Design
- Business Intelligence Reporting

## Task 1: Prepare the Data
I start to explore and integrate the dataset into Power BI and deal with the uncleaned data. 
Then, using Power Query Editor, I will clean and mash up the data to use it for reporting.

Case study scenario:
- Analyze manufacture’s sales internally
- Comparing sales against other competitors
- Comparing product performance against other competitors

1. Load all the required data.
2. Clean and explore by removing unnecessary columns. Replace null values by fill-down function.
3. Split the values by "Columns from example" and ensure the data types are correctly formatted.

![image alt](https://github.com/kristineng/PowerBI_Competitor-Sales-Analysis/blob/f23c4f17e407b0e1c6e944e07291265939b7e998/Photos/Screenshot%202026-05-22%20080412.png)

4. Remove uncessary rows. Transpose the table to ensure correct structure.
5. Append the queries: combine both Sales tables and create a single table that analyzes sales for all countries.
6. Have a quick exploratory analysis by using (View - Column Profile - Column Statistics and Value Distribution)
7. Review the last 3 years by Filter Rows.
8. Create Clustered Column Charts to determine which manufactures generate most value.

![image alt](https://github.com/kristineng/PowerBI_Competitor-Sales-Analysis/blob/3abfcd56d0d54f0ffcd97669379cfc25561a606f/Photos/Screenshot%202026-05-21%20225049.png)

9. Setting up relationship between tables
10. Create new table using DAX
    Formula: Date = CALENDAR(DATE(2019,1,1), DATE(2021,12,31))

![image alt](https://github.com/kristineng/PowerBI_Competitor-Sales-Analysis/blob/faea517e8bbd820df8d2fa77befa3ebc639ffc2e/Photos/Screenshot%202026-05-22%20081454.png)

## Task 2: Discover Business Insights
1. Using top N list to identify major competitors.
2. Choosing the Stacked column chart to see how the values of each manufacturer contribute to the totals.
3. Select an appropriate visual that displays Revenue over time (Clustered Column chart). Add slicers and ensure Data labels, Target labels, and Callout value are all enabled.
4. Add some more dimensions and create a hierarchy of Category, Segment, Product to analyze in-deep about Revenue (using Matrix visual)
5. To show the sales growth and the rate at which a product can increase the revenue from sales, using DAX calculations. Select the maxtrix visual and drag PY Sales and % Growth in values section.
6. Apply conditional formatting rule for Revenue by Category visualization:
- 0-40%: Red
- 41-60%: Yellow
- More than 60%: Light Blue

![image alt](https://github.com/kristineng/PowerBI_Competitor-Sales-Analysis/blob/678553cf650e381c7aa1c41d4b867eb7485b2d7f/Photos/Screenshot%202026-05-22%20062214.png)

## Task 3: Finalize Data Visualization
### Overview

![image alt](https://github.com/kristineng/PowerBI_Competitor-Sales-Analysis/blob/e50e49579ba43994754d975e8a6f1152a79acde7/Photos/Screenshot%202026-05-22%20070636.png)

### Key Findings:
1. Sintec has total market share of 38.22% in the USA.
2. 2021 Q1 experienced the highest year-over-year growth rate with 18.8%.
3. Artisans emerged as the dominant competitor in Germany, holding over 50% market share.
4. Sintec maintained solid global market share growth compared to competitors with 21.15%.

#### For details of each data professions, please download the PowerBI file.

Thank you!


