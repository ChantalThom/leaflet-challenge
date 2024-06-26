# leaflet-challenge
Module 15 Challenge

The United States Geological Survey, or USGS for short, provides scientific data about natural hazards and the impact of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

<p align='center'> <img src='Leaflet-Part-1/Images/1-Logo.png'></p>

# 1st Task
# Retrieve the Data Set
The USGS provides feeds, some which are realtime, of all major geological events on their website through JSON API feeds.
<p align='center'> <img src='Leaflet-Part-1/Images/3-Data.png'></p>

# Create Map
- TileLayer loads without error 
- Connects to geojson API using D3 without error
  <p align='center'><img src='Leaflet-Part-1/Images/4-JSON.png'></p>
- Markers with size corresponding to earthquake magnitude 
- A legend showing the depth and their corresponding color

# Sample Map
  <p align='center'><img src='Leaflet-Part-1/Images/Sample Map.png'></p>
  
# Data Points 
- Data points scale with magnitude level 
- Data points colors change with depth level
- Each point has a tooltip with the Magnitude, location and depth
- All data points load in the correct locations
  <p align='center'><img src='Leaflet-Part-1/Images/5-Advanced.png'></p>

