# Overview

Built with JavaScript, Leaflet.js, and D3.js, this project visualizes earthquake data from the USGS GeoJSON Feed by plotting seismic activity on an interactive map. The map dynamically represents earthquake magnitude through marker size and depth through color, with popups providing additional details. A legend is included for better data interpretation, and an optional enhancement allows for plotting tectonic plates alongside earthquake data.

# Project Components

__1. Data Retrieval and Processing__:
Retrieves earthquake data from the USGS GeoJSON Feed.
Parses JSON to extract relevant details, including:
Longitude & Latitude – for map plotting.
Magnitude – determines marker size.
Depth – influences marker color.
Location & Time – displayed in tooltips.

__2. Earthquake Visualization__:
Uses Leaflet.js to generate an interactive map.
Markers represent earthquakes, scaled by magnitude and colored by depth.
Popups display earthquake details when clicked.
Legend explains color depth representation.

__3. Optional Enhancement: Tectonic Plate Overlay__:
Adds tectonic plate boundaries from GitHub’s tectonic plates dataset.
Enables toggling between different base maps.
Implements layer controls for independent dataset visibility.

# Files

__index.html:__ Structure for the interactive map.

__app.js:__ JavaScript logic for data fetching, visualization, and interactivity.

__style.css:__ Optional styling for the map.

# Key Features

__Earthquake Data Visualization__:
Maps earthquake locations based on longitude and latitude, with markers dynamically scaled by magnitude and color-coded by depth to indicate severity. Popups display earthquake details, and a legend explains the depth-color relationship. An optional tectonic plate overlay includes boundary plotting, multiple base map options, and overlay controls for better visualization.

# Dependencies

__Data Handling__:
Uses D3.js to fetch and parse GeoJSON data.
Extracts magnitude, depth, and location details.
Map Rendering
Uses Leaflet.js for interactive map creation.
Implements tile layers for base map customization.
Plots earthquake markers and overlays tectonic plates.
Technologies Used

__JavaScript__: Primary programming language for data processing and visualization.
Leaflet.js – Library for interactive map rendering.
D3.js – Fetches and processes earthquake data from the USGS API.
GeoJSON – Format for earthquake and tectonic plate data.

# How to Use

1. Clone this repository to your local environment.
2. Open index.html in a web browser.
3. The map will automatically load earthquake data and visualize it.
4, Click on markers to view earthquake details.
5. (Optional) Enable the tectonic plate layer for additional insights.

<!--Mod 15-->
