# mapping-earthquakes

## Overview of Analysis
The purpose of this project is to create data visualizations for the Disaster Reporting Network. Geographical maps will be populated with geoJSON earthquake and tectonic plate data from the US Geological Survey Website. 

## Results
visualizations with interactive features on earthquakes from around the world were made. A user can pick between three different map styles: 'streets', 'Satellite Streets', and 'dark'. Earthquake data, tectonic plate boundaries, and major earthquakes can all be toggled on and off on the map as well. The way the earthquake data points have been displayed correlates to the earthquake's magnitude. larger data points that are darker red are high magnitude earthquakes. Points that are small and lighter in color are representative of smaller earthquakes. Any point can be clicked on to display that earthquake's magnitude and location. 

## Summary
geoJSON data from the US Geological Survey website was retrieved using JavaScript as well as the D3 and leaflet library and plotted on a mapbox map through an API request. A popup marker shows the location and magnitude of each earthquake.


