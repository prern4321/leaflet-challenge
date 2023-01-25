# leaflet-challenge
Visualizing data with leaflet 
This project utilizes leaflet, Javascript and HTML to visualize the earthquake data from the United States Geological Survey (USGS).The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. In this challenge, we have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

Part-1: Basic Visualization (leaflet_step1)
Get the Data Set
The USGS provides earthquake data in a number of different formats, updated every 5 minutes
The "All Earthquakes from the Past 7 Days" data set was selected from the USGS GeoJSON Feed page
The data was given in JSON format which was used to pull in the data for the visualization

Import and Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

The data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color
Earthquakes with higher magnitudes appear larger and earthquakes with greater depth should appear darker in color
Popups that provide additional information about the earthquake were included when a marker is clicked
A legend was created to provide context for the map data

![image](https://user-images.githubusercontent.com/112128775/214452856-2252e72e-c6a1-492f-8ed2-8cad6b551963.png)


Part-2: More Data (leaflet_step1)
Plot a second data set on the map above to illustrate the relationship between tectonic plates and seismic activity.

Pull in Tectonic Plates data set
Visualize it along side the original set of data
Add a number of base maps (Satellite Map, Grayscale Map, Outdoors Map and Dark Map) to choose from
Separate out the two different data sets (earthquakes and tectonic plates) into overlays that can be turned on and off independently
Add layer controls to the map.

[image](https://user-images.githubusercontent.com/112128775/214453044-fd7994d3-e0e1-480d-bd2f-e6426de50b39.png)

Please note that leaflet _step1 creates the Earthquake visualization  and leaflet_step2  plots the second dataset o our map to illustrate the relationship between tectonic plates and seismic activity. The index.html and the static folder on the main page brings both the visualizations together.

![image](https://user-images.githubusercontent.com/112128775/214453225-6ca67b78-f618-41b5-8d3a-2e0044c76d15.png)



