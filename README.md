# Covid_19_Analysis

# Objective
The purpose of this project is to analyze COVID-19 cases and vaccination data in India to gain insights into the spread, recovery, and vaccination trends across various states. The analysis includes key metrics like active cases, death rates, recovery rates, and vaccination distribution by gender and state. This project also aims to highlight the top states with the highest number of cases and vaccinations, providing actionable insights for healthcare decision-making.

# Dataset
The project uses two datasets:

COVID-19 Cases Dataset: Contains daily COVID-19 statistics, including confirmed cases, recoveries, and deaths across Indian states and Union Territories.
COVID-19 Vaccination Dataset: Provides data on the number of vaccine doses administered, categorized by gender and age groups, across Indian states.

Tools and Libraries Used

Pandas: For data manipulation and cleaning.

Numpy: For numerical operations.

Matplotlib and Seaborn: For data visualization, particularly bar charts and line plots.

Plotly Express: For interactive visualizations like pie charts.

Datetime: For handling date formats.

# Main Steps
1. Data Cleaning
   
Removed extra columns we didn’t need.

Changed the date format so we could analyze the data by day.

Filtered the data to focus on important parts like active cases and vaccination numbers.

2. COVID-19 Case Analysis
   
Found the number of active cases by subtracting recoveries and deaths from total confirmed cases.

Created a table showing confirmed cases, deaths, and recoveries by state.

Calculated the Recovery Rate and Mortality Rate for each state.

Identified the top 10 states with the most active cases and highest deaths, using bar charts.

3. Vaccination Analysis
   
Cleaned up the vaccination data and renamed some columns for easier reading.

Compared the number of vaccines given to males and females using a pie chart.

Found the top 6 states with the highest vaccinations and showed them in a bar chart.

4. Growth Trend
   
Made a line chart showing how the number of active cases grew over time for the top 5 states most affected by COVID-19.
Visualizations

Bar charts for top states by active cases, deaths, and vaccinations.

A pie chart showing the split between male and female vaccinations.

Line charts showing how cases grew in major states.
