# PyBer_Analysis
## Background
### PyBer Analysis Overview
This project utilized python/pandas in jupyter notebook to analyze ride-sharing data from the company PyBer, a Python-based ride-sharing application. As a new analyst for PyBer, my job was to accurately analyze the data and create compelling visualizations from my analyses to present to the company's CEO.

Two files in .csv format (city_data.csv; ride_data.csv) were provided as starting points for this project. The city_data.csv file contains data in the following columns: city, driver count, and type. The ride_data.csv file contains data in the following columns: city, date, fare, and ride_id. Data from both files was imported, manipulated, and then aggregated into python/pandas dataframes for accessible viewing/analysis.

### Challenge Overview
This challenge encompassed creating a summary DataFrame of the ride-sharing data by city type and a multiple-line graph showcasing the total weekly fares for each city type. I began by downloading the challenge starter code, and by manipulating the data, calculated the following: total rides, total drivers, total fares, average fare per ride, and average fare per driver, for the three city types (rural, suburban, and urban). This data was organized to create a summary dataframe.

After creating the summary dataframe, the original dataframe was reorganized and grouped by date/type to create a pivot table. Finally, the pivot table was 

The final file with the code to alter the data for this challenge is: PyBer_Challenge.ipynb.

## Results

As seeen in the following graphs, there are significant differences in the ride-sharing data between the three types of cities. This first chart indicates that of the three types of cities, urban cities have most rides per city with lower fares; rural cities are the opposite, with fewer rides at higher prices. In addition, the size of the points indicate the number of drivers: urban cities have the most drivers, while rural cities have the fewest.

**Ride-Sharing Data (2019)**
![Ride-Sharing Data (2019)](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig1.png)

The following box and whisker plots also showcase this data:

**Ride Count Data (2019)**
![Ride Count Data (2019)](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig2.png)

**Ride Fare Data (2019)**
![Ride Fare Data (2019)](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig3.png)

**Driver Count Data (2019)**
![Driver Count Data (2019)](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig4.png)

Additionally, the percent of total fares, total rides, and total drivers are displayed in the following pie charts. Urban cities have the highest percentage for all three categories.

**% of Total Fares by City Type**
![% of Total Fares by City Type](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig5.png)

**% of Total Rides by City Type**
![% of Total Rides by City Type](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig6.png)

**% of Total Drivers by City Type**
![% of Total Drivers by City Type](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Fig7.png)

This final multiple line chart displays the total fare by city type. As easily recognizable by this graph, rural cities have the highest fares per ride, while urban cities have the lowest fares.

**Total Fare by City Type**
![Total fare by City Type](https://github.com/marikachrisanthopoulos/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png)


## Summary
