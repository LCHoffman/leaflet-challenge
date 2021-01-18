# Leaflet Challenge

## Background
Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!  The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

## Earthquake Magnitude Visualization
Create a map using Leaflet that plots all of the earthquakes from data set based on their longitude and latitude.
 * Data markers should reflect the magnitude of the earthquake by their size and and depth of the earth quake by color.
 * Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.
 * Include popups that provide additional information about the earthquake when a marker is clicked.
 * Create a legend that will provide context for your map data.

## Notes
 1. I have color vision deficits which can mean color coding markers more difficult.  I tend to stay away from color scales that involve shades of the same color OR colors that transition directly from green to red.  I created a color scale that used distinguishable colors in blue, green, yellow and red families.  I also outlined the markers with black so that they were more easily visible on the street and satellite maps.  With my deficient color vision, markers without the black outline "disappear" into the map.
 2. In order to get the white background on the legend to display, I created a new class in the CSS file.
 
 ## Sample Map
 ![Image of Map] (https://github.com/LCHoffman/leaflet-challenge/blob/main/Map-Example.png)
