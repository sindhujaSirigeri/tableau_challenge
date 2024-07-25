# tableau_challenge

# Citi Bike Data Analysis - 2020

## Project Overview

This project involves the analysis of Citi Bike data for the year 2020, specifically focusing on the months of March, June, September, and December. The analysis aims to provide insights into the usage patterns, ridership trends, and other key metrics of the Citi Bike program during these months.

## Tableau Public Visualization

You can view the interactive visualizations and dashboards on Tableau Public by following this link: [Tableau Public: Citi Bike Data Analysis - 2020](https://public.tableau.com/shared/HF5DNY7SF?:display_count=n&:origin=viz_share_link)


## Data Sources

The data used in this analysis was sourced from the Citi Bike Trip History Logs, which are publicly available on the Citi Bike Data webpage. The specific datasets used are:

-   March 2020: `202003-citibike-tripdata.csv`
-   June 2020: `202006-citibike-tripdata.csv`
-   September 2020: `202009-citibike-tripdata.csv`
-   December 2020: `202012-citibike-tripdata.csv`
You can access the data from the following link: [Citi Bike System Data](https://citibikenyc.com/system-data)

## Analysis Performed

1.  **Data Loading and Preparation**:
    
    -   Loaded the CSV files for the specified months.
    -   Combined the datasets into a single dataframe for comprehensive analysis.
2.  **Key Metrics Analyzed**:
    
    -   Total number of trips recorded each month.
    -   Ridership growth and trends.
    -   Peak hours of bike usage for each month.
    -   Analysis of top and bottom stations for starting and ending journeys.
    -   User type distribution and average trip duration.
3.  **Visualization and Reporting**:
    
    -   Created various visualizations to represent the key metrics and insights.
    -   Designed dashboards to provide a clear and concise overview of the analysis.
    -   Developed a Tableau story to present the findings in an interactive format.

## Visualizations

The following visualizations were created to support the analysis:

1.  **Total Trips per Month**: A bar chart showing the total number of trips for each analyzed month.
2.  **Peak Usage Hours**: Line graphs indicating the peak hours of bike usage during the analyzed months.
3.  **Top and Bottom Stations**: Maps and bar charts displaying the top 10 and bottom 10 stations for starting and ending journeys.
4.  **User Type Distribution**: Pie charts showing the proportions of short-term customers and annual subscribers.
5.  **Average Trip Duration**: Bar charts comparing the average trip duration for different user types.

## How to Use

1.  **Tableau Workbook**: The analysis and visualizations are available in a Tableau workbook. You can access the Tableau Public profile to view the interactive dashboards and story.
2.  **CSV Files**: The raw data files used for the analysis are included in the `data` directory of this project.
3.  **Python Scripts**: The scripts used for data loading, preparation, and analysis are included in the `scripts` directory.

## Conclusion

This analysis provides valuable insights into the usage patterns and trends of the Citi Bike program in 2020. Key findings include:

1.  **Total Trips per Month**:
    
    -   There were significant variations in the total number of trips across the analyzed months. Sep had the highest number of trips, indicating peak usage during the summer.
    
2.  **Ridership Growth and Trends**:
    
    -   Ridership showed a steady increase from June to Sep, followed by a decline towards December, likely due to seasonal factors.

3.  **Peak Usage Hours**:
    
    -   Peak usage hours were typically in the morning and evening, correlating with commuter traffic. However, during summer months, midday peaks were also observed.

4.  **Top and Bottom Stations**:
    
    -   The top stations for starting and ending journeys were concentrated in high-traffic areas such as business districts and tourist attractions. Conversely, the bottom stations were located in less densely populated areas.

5.  **User Type Distribution**:
    
    -   The majority of users were annual subscribers, but there was a noticeable increase in short-term customers during the summer months.

6.  **Average Trip Duration**:
    
    -   Annual subscribers had shorter average trip durations compared to short-term customers, suggesting that subscribers used bikes for commuting, while short-term customers used them for leisurely rides.

These insights can help city officials and program administrators make informed decisions to improve the bike-sharing program and promote sustainable transportation in New York City. By understanding usage patterns and trends, the program can be optimized to better serve the needs of its users.
