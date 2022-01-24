# JVWCD-Spring-2022

## Explination of Files

### R Files

***JVWCD-Spring-2022.Rproj***
> If you open this and then open the rmd file you should be able to work from R studio and access the csv or xlsx files.

***eda.Rmd*** is the code for our EDA assignment. We can each create a branch and each have our own version of this or we can take turns pushing an pulling and workin on specific parts.

### XLSX Files
***System_Demand_and_Weather_Data.xlsx*** is the incomplete dataset with not all of 2021.

***System Demand and Weather Data 2021.xlsx*** is the latest dataset from Clifton with all of 2021 data. Looks like it has 2020 and 2021

### CSV Files

***2_year_system_demand.csv*** is the two year system demand sheet in CSV format from the System Demand and Weather Data 2021.xlsx file.

***system_demand_by_point_type.csv*** is the system demand by point sheet in CSV format from the System Demand and Weather Data 2021.xlsx file.

***weather_sl_airport.csv*** is the weather data that was in the System Demand and Weather Data 2021.xlsx file.

## Notes

+ (From Zach) The first thing I did in the rmd file was to get the dates in a consistent format. I figured wed want the same format to be able to look at the same day or hour between the data frames.

## Questions

+ There is a NULL value in the 2 year system demand table. What do we do with NULL's?
+ The grain for weather data is daily. Do we want the model output to be daily or hourly?
+ If we want the output to be daily how should we agregate the hourly demand to get daily?
