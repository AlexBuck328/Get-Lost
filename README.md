# Get-Lost
The COVID-19 Pandemic and subsequent mitigation efforts have left people in need of asomething to break the monotony of lockdown-life. Get Lost is a useful tool for planning your Montana outdoor adventure. Select a recreation spot to find the distance to the nearest airport.

## Data Aquisition

I obtained Montana GNIS data for airport and forest locations here:
https://mslservices.mt.gov/Geographic_Information/Data/DataList/datalist_Details.aspx?did=%7B0c57ebe2-f8e8-4d55-b159-ab3202898956%7D

Montana Fish, Wildlife & Parks Recreation Area data here:
https://gis-mtfwp.opendata.arcgis.com/datasets/montana-fish-wildlife-parks-lands

## Data Cleaning

GNIS data was cleaned using Node scripts to filter files for airports as well as forests. Mapshaper was used to convert the Fish, Wildlife & Parks shapefiles to JSON. 

