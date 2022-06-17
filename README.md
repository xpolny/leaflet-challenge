# Leaflet Homework: Visualizing Data with Leaflet

## Level 1: Basic Visualization

### Dataset
Earthquake data from the last 7 days is being used for these visualizations. The data is being brought in as a JSON from the [USGS](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php), which is updated every 5 minutes.

### Visualization
Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

This visualzation includes
   * Data markers which indicate the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color

   * A legend that will provide context for your map data

   * Popups that show additional information about the earthquake when a marker is clicked.

![Step-1](Images/Leaflet_Step_1.png)

Access the Level 1 page [here](https://xpolny.github.io/Leaflet-Challenge/Leaflet-Step-1/index.html)


## Level 2: Advanced Visualization

### Additional dataset
[Tectonic plates](https://github.com/fraxen/tectonicplates) were added in this map in order to illustrate the relationship between tectonic plates and seismic activity.

### Visualization

* A base map object with 4 layers to choose from was added 
* Layer controls were added
* An overlay map that shows plates layer and geoJSON layer were also added

![Step-2](Images/Leaflet_Step_2.png)

Access the Level 2 page [here](https://xpolny.github.io/Leaflet-Challenge/Leaflet-Step-2/index.html)
