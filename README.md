# Surfs_up

## Overview

This analysis queries the database - hawaii.sqlite and  finds the temperature data for specific months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources

    - hawaii.sqlite 

## Tools used

    - Python 3.7
    - SQL alchemy toolkit & ORM

## Results

### Deliverable - 1 : Summary Statistics for June

    - June temperatures retrieved filtered by the date column of the measurement table.
    - List of temperatures added to a list.
    - List of temperatures converted to a Pandas DataFrame
    - Summary Statistics generated for the DataFrame.
    - Number of stations available in the dataset determined
    - Most active station determined and list of stations and counts displayed in descending order.
    - For most active stations - lowest, highest and average precipitation data determined.


### Deliverable - 2: Summary Statistics for December

    - December temperatures retrieved filtered by the date column of the measurement table.
    - December temperatures added to a list.
    - DataFrame created from the list of December temperatures.
    - Summary statistics generated.
    - Data filtered for the station with highest precipitation observations for the month of December.
    - December precipitation data plotted on a histogram.

## Summary:

For the month of June the minimum temperature was 53 deg, the maximum temperature was 87 deg and mean temperature was 73.1 deg. This is based on temperature data of 19550 days.

For the month of December the minium temperature was 56 deg, the maximum temperature was 83 deg and mean temperature was 71 deg. This is based on temperature data of 1517 days.

Additionally, for the month of June the max precipitaton was 9.64, the minimum was 0 and average was 0.21. This is based on 2772 counts of data of the most active station.

Also, for the month of December the  max precipitaton was 9.64, the minimum was 0 and average was 0.21. This is based on 2772 counts of data of the most active station.