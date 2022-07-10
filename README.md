# Surfs_up

## Overview

This analysis queries the database - hawaii.sqlite and  finds the temperature and precipitation data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources

   - hawaii.sqlite 

## Tools used

   - Python 3.7, Pandas, Numpy
   - SQL alchemy toolkit & ORM, Jupyter Notebook

## Results

### Deliverable - 1 : Summary Statistics for June

   - June temperatures retrieved filtered by the date column of the measurement table.
   - List of temperatures added to a list.
   - List of temperatures converted to a Pandas DataFrame
   - Summary Statistics generated for the DataFrame.
   - Number of stations available in the dataset determined
   - Most active station determined and list of stations and counts displayed in descending order.
   - For most active stations - lowest, highest and average precipitation data determined.

   <img width="127" alt="June_Temps" src="https://user-images.githubusercontent.com/104603128/178156600-e45a3e59-361a-4866-94ee-97fd69d4168d.png">
    Figure - 1: Temperature Summary Statistics for June
    


### Deliverable - 2: Summary Statistics for December

   - December temperatures retrieved filtered by the date column of the measurement table.
   - December temperatures added to a list.
   - DataFrame created from the list of December temperatures.
   - Summary statistics generated.
   - Data filtered for the station with highest precipitation observations for the month of December.
   - December precipitation data plotted on a histogram.
   
   <img width="157" alt="December_Temps" src="https://user-images.githubusercontent.com/104603128/178156643-63c02934-089c-47f9-950d-af75f49bd725.png">
    Figure - 2: Temperature Summary Statistics for December
    
   <img width="377" alt="Precipitation_Histogram" src="https://user-images.githubusercontent.com/104603128/178156727-3b3a753d-9afc-4da3-8a26-3cdf02900327.png">
    Figure - 3: Precipitation Histogram for December (most active station) 
    
    

## Differences between June and December Weather

   - The maximum temperature for June is more than December.
   - The minimum temperature for June is slightly more than December.
   - The average temperatures for June are slightly more than December.
   - The precipitation is higher in the month of December as compared with June.

## Summary:

   - For the month of June the minimum temperature was 64 deg, the maximum temperature was 85 deg and mean temperature was 75 deg. This is based on temperature data of 1700 days.

   - For the month of December the minimum temperature was 56 deg, the maximum temperature was 83 deg and mean temperature was 71 deg. This is based on temperature data of 1517 days.

   - Additionally, for the month of June the max precipitaton was 1.39, the minimum was 0 and average was 0.15. This is based on 2772 counts of data of the most active station.

   - Also, for the month of December the  max precipitaton was 3.14, the minimum was 0 and average was 0.24. This is based on 2772 counts of data of the most active station.

Similar analysis for other months can be done to determine overall weather trend.
