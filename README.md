# PyBer_Analysis

## Overview of the analysis

### Purpose 

Help Pyber improve access to ride sharing services and determine affordability under certain neighbourhoods by analyzing it's rideshare data from January to early May of 2019 
and creating a compelling visualization for the CEO, V. Isualize with manager Omar.

### Analysis components
- Create a summary DataFrame of the ride-sharing data by city type
- Create a multiple-line graph that shows the total weekly fares for each city type
- Submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer

### Resources
Tools:
- Python 3.7
  - Pandas
  - Matplotlib
- Jupyter Notebook 6.3

Data Source:
- city_data.csv
- ride_data.csv

## Results

  describe the differences in ride-sharing data among the different city types
  
  Pyber Ridesharing data for each city-type
  
  ![Summary DataFrame](https://github.com/Sheetaltkr/PyBer_Analysis/blob/main/analysis/Pyber_summary_dataframe.png)
  
  Findings from the ridesharing summary:
  
   **Total Rides**
   
   -   Urban cities have highest total rides **(68.4%)** 
   -   Rural cities have lowest total rides **(5.3%)**
   -   Suburban cities have moderate total rides **(26.3%)** 
   -   Suburban city rides are 5x times Rural city rides
   -   Urban city rides are 13x times Rural city rides
    
   **Total Drivers**
   
   -   Urban cities have highest Driver count **(80.9%)**
   -   Rural cities have lowest total rides **(2.6%)**
   -   Suburban cities have moderate total rides **(16.5%)** 
   -   Suburban city rides are **6x** times Rural city rides
   -   Urban city rides are **31x** times Rural city rides
   
   **Total Fare**
   
   -   Urban cities have highest total fare **(62.7%)** 
   -   Rural cities have lowest total fare **(6.8%)**
   -   Suburban cities have moderate total fare **(30.5%)** 
   -   Suburban city total fare is **~5x** times Rural city fare
   -   Urban city total fare is **~9x** times Rural city fare
  
   **Average Fare per Ride**
   
   -   Rural cities have highest average fare per ride **34.6**
   -   Urban cities have lowest average fare per ride **24.5**
   -   Rural average fare per ride is **~1.5x** times Urban average fare per ride


   **Average Fare per Driver**
   
   -   Rural cities have highest average fare per driver **55.5**
   -   Urban cities have lowest average fare per driver **16.6**
   -   Rural average fare per driver is **~3x** times Urban average fare per driver

   **Summary**
   
   -   Due to the fact that Urban cities are highest populated, Rural cities are lowest populated and Suburban are moderately populated 
   -   The ride share demand is highest in Urban and lowest in Rural cities
   -   Higher demand requires more drivers and higher rides, hence highest fare collections
   -   Lower demand means less no. rides, less no. drivers and hence lowest fare collections
   -   In Rural cities, due to longer distances between the ride starting and ending points and lower no. of rides the Average Fare per Ride and Average Fare per Driver is              highest.
   -   In Urban cities, due to shorter distances between the ride starting and ending points and higher no. of rides the Average Fare per Ride and Average Fare per Driver is            lowest. 

  Pyber Ridesharing multiple line chart
  
  ![Pyber_fare_summary](https://github.com/Sheetaltkr/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)
  
## Summary

  Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
