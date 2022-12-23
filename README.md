# Today's Traffic Accidents in Austin

By running the entire notebook we will visualize an up to date visulization of Traffic Accidents in Austin, Clusters of Accidents and a Statistical Analysis of the Records of Accidents.

  1. Data comes from https://data.austintexas.gov/Transportation-and-Mobility/Real-Time-Traffic-Incident-Reports/dx9v-zd7x
  
  2. It is necessary to authenticate the API to get the full dataset
  
  3. ZIP code shapefiles are in this repository. https://github.com/mnovovil/AustinTrafficAccidentsToday/blob/main/ZIP%20Code%20Data.zip

# Visualizations

## All accidents in one day (Most granularity)

<img src="https://github.com/mnovovil/AustinTrafficAccidentsToday/blob/main/point_data_viz.png" width="50%" height="50%">

## All accidents in one day (ZIP code level)

<img src="https://github.com/mnovovil/AustinTrafficAccidentsToday/blob/main/zip_data_viz.png" width="50%" height="50%">

## HotSpots and ColdSpots

<img src="https://github.com/mnovovil/AustinTrafficAccidentsToday/blob/main/hotspot.png" width="50%" height="50%"> 

# Spatial & Spatio Temporal Clusters of Accidents 


## Spatial Clusters (DBSCAN)

<img src="https://github.com/mnovovil/AustinTrafficAccidentsToday/blob/main/spatial_clusters.png" width="50%" height="50%"> 

## Spatial-Temporal Clusters (ST-DBSCAN)

<img src="https://github.com/mnovovil/AustinTrafficAccidentsToday/blob/main/spatio_temporal_clusters.png" width="50%" height="50%"> 
