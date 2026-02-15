# Indian Web Series Ratings Analysis – Power BI Dashboard

## Project Objective
Analyze user ratings of Indian web series to identify the most popular and highest-rated shows using Power BI.

## Dataset
Indian Web Series User Ratings dataset (Kaggle)

## Steps Performed

### 1. Data Cleaning
- Replaced missing rating values (0) with null
- Verified data consistency
- Removed incomplete observations

### 2. Data Transformation
- Converted data from wide format to long format using Power Query (Unpivot)
- Created structured dataset with:
  - User_ID
  - Series
  - Rating

### 3. Data Analysis
- Calculated Average Rating per series
- Calculated Popularity (Number of Ratings)
- Identified Top 10 series by rating

### 4. Data Visualization
- KPI Card: Average Rating
- Bar Chart: Top 10 Series
- Scatter Chart: Popularity vs Rating

## Tools Used
- Power BI
- Power Query
- Data Cleaning
- Data Transformation
- Data Visualization
