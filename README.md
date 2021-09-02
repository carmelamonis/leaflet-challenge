## Summary

![1-Logo](Images/1-Logo.png)

The United States Geological Survey, USGS for short, provides scientific data about natural hazards and the health of our ecosystems and environment. This includes earthquake data from all over the world, which gets updated every 5 minutes. 

The [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) provides several data sets that return the earthquake information in JSON format. I chose [All Earthquakes from the Past 7 Days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) for this challenge.

## Scope
I pulled in the data using the USGS GeoJSON data set of All Earthquakes from the Past 7 Days to use for my visuaization.

I used Leaflet to create the plots of all of the earthquakes from the data set based on their longitude and latitude.

The data markers reflected the magnitude of the earthquake by their size, and the depth of the earthquake by its color. Earthquake information is included in the popup when the marker is clicked.
