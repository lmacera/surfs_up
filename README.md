# Surfs-Up Analysis
## Project Overview
Our team has decided to partner with W. Avy to open a surf and ice cream shop in Oahu. Before choosing a location W.Avy would like our teams help analyzing the temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
## Resources
- Data Source: hawaii.sqlite
- Software: SQL, Jupyter Notebook, Python, Pandas functions and methods, and SQLAlchemy
## Results 
From our analysis we created 2 dataframe showing the temperatures of June and December. From these dataframes we were then able to produce the summary statistics on temperature for both June and December. 
### June Temperature Analysis
From the below dataframe image we can see:
-	The total number of temperature data point from which the June statistical analysis was created is 1700
-	The average temperature for June is about 75 degrees Fahrenheit 
-	The minimum temperature in June is 64 degrees Fahrenheit
-	The maximum temperature in June is 85 degrees Fahrenheit
![ June_temps.PNG]( https://github.com/lmacera/surfs_up/blob/main/June_temps.PNG )
### December Temperature Analysis
From the below dataframe image we can see:
-	The total number of December temperature data point from which the statistical analysis was created is 1517
-	The average temperature for December is about 71 degrees Fahrenheit 
-	The minimum temperature in December is 56 degrees Fahrenheit
-	The maximum temperature in December is 83 degrees Fahrenheit
![ December_temps.PNG]( https://github.com/lmacera/surfs_up/blob/main/December_temps.PNG  )
### June to December Comparison
From the above dataframes and analysis our team found:
-	There are more data point available for analysis in June. Though there are only approximately 200 more data points in June this could throw off the analysis when comparing June and December temperatures.
-	The minimum temperature is lower in December, but maximum temperatures do not change that drastically between June and December
-	Average temperature is higher in June but does not change drastically from the average temperature in December 

##Summary
In summary June and December have similar temperatures and have great potential for a surf and ice cream shop. Further analysis that can be run for this a would be to:
1.	Run a statistical analysis for all months to make sure the temperature is ideal for the majority of the year.
2.	Run an analysis on the precipitation rates for each month to ensure the best weather for surfing and ice cream.
3.	Evaluate the population and visitation frequency at each location to find the most ideal location for a shop compared to its temperature statistics.
 

