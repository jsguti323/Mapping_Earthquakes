# Mapping Earthquakes

## Overview
The goal of this project was to create a data visualization that shows the difference in magnitudes of earthquakes all over the world during the previous seven days. Using the Javascript and D3 library, we were able to use a URL for geoJSON earthquake data to retrieve geographical coordinates and magnitudes, then added them to an interactive map using the Leaflet library via an API request. 

## Results

### Streets: All Layers
![streets_all_layers](https://user-images.githubusercontent.com/99751636/171505611-26eba02d-a46f-4115-a406-3198fffe61a6.png)

### Streets: Earthquakes
![streets_earthquakes](https://user-images.githubusercontent.com/99751636/171505627-d613b1a0-4620-47cc-ad68-5211ea32d201.png)

### Streets: Tectonic Plates
![streets_tectonic_plates](https://user-images.githubusercontent.com/99751636/171505644-d6b10333-b934-4afd-a90b-277e2f9666dd.png)

### Streets: Major Earthquakes
![streets_major_earthquakes](https://user-images.githubusercontent.com/99751636/171505662-d18491e6-1a51-48b7-a63f-0aaea19c240a.png)

### Satellite: All Layers
![satellite_all_layers](https://user-images.githubusercontent.com/99751636/171505852-3f7a4667-ac8e-43c3-9286-95e47de8c9ea.png)

### Navigation (Night): All Layers
![navigation_all_layers](https://user-images.githubusercontent.com/99751636/171505709-0527a12f-6ef5-47ed-93d2-33bc01375366.png)

## Summary
For the base layer of map, the user has 3 styles to choose from:
* Streets
* Satellite Streets
* Navigation (night)

Once the user has selected their base layer for the map, they can then select which data they wish to view. Their options are:
* All earthquakes in the last 7 days
  * Denoted by circle markers.
  * Color of marker is indicative of magnitude of that earthquake.
  * Legend provided in bottom left corner of map allows the user to associate the color of the marker with the severity of the earthquake.
* All earthquakes in the last seven days with a magnitude of 5.0 or higher.
* The outlines of tactonic plates across the globe.

The user can choose to view all options, no options, or any combination of the options.
