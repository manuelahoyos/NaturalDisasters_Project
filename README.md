# Natural Disasters Analysis
Group project in which data about natural disasters around the globe were analyzed and results were visualized using Python, Pandas, Matplotlib, JavaScript, D3 and HTML/CSS.
The objective was to analyze if the change in average land temperature has an effect on magnitude of earthquakes, number of earthquakes with magnitudes of 5.5 and higher, number of tsunamis and number of volcanic eruptions. 

## Average Land Temperature Change Over the Years:

The dataset 'GlobalLandTemperatures_ByCountry.csv' was cleaned using Python and Pandas, to extract the average land temperature of specific countries during the years 1960 - 2013. The average land temperature for these countries was plotted against the years to analyze the change over time using Matplotlib. 

<img src="images/land_tempIndex.png" width="900">

## Number of Tsunamis Over the Years:

Historical_Tsunami_Event_Locations.csv

## Number of Volcanic Eruptions Over the Years:
volcanoes.csv

## Number of Earthquakes Over the Years:
earthquakes.csv

## Comparison:


## Comparison of Average Land Temperature and Earthquake Magnitude Using JavaScript and D3:

The datasets ‘GlobalLandTemperatures.csv’and ‘Earthquakes.csv’ were cleaned using Python and Pandas to calculate the average land temperature and the average magnitude of earthquakes during the years 2000 - 2012. This data was selected for the countries Turkey, Iran, Greece and Pakistan and the finalized DataFrames were exported as csv files. 

The comparison between average land temperature and average magnitude of earthquakes was plotted using JavaScript and D3. A scatterplot was created within the temp.js file using JavaScript and D3. The data was pulled from the csv files and the d3.select() function was used to append the graph into the HTML file. CSS was used for both the HTML page styling and the scatterplot styling. D3 was used for animations, transitions, click events on the y labels, and tooltips when the cursor hovers over the state circles.

<img src="images/D3graphs.png" width="900">

