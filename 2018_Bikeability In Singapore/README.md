# Undergrad GIS Group Project

For course RE2301: GIS for Real Estate. 
Completed: Year 2018

## Topic: Bikeability in Singapore 
Fun fact: Back then we were seniors taking a lower level module, so we thought why don't we proceed to choose a fun topic that allows us to overkill and demonstrate all the GIS skills we had? :') 

Bikeability was therefore the interesting topic chosen for the aspiring urban planners that we were. 

<img src="Pictures/dalle_bikeability.png" width="500">

_Image generated using DALLE 3_


We wanted to evaluate bikeability throughout Singapore following the work of Van Dyck et al. (2012) and Winters et al. (2012), which created a Bikeability Index that essentially quantifies the factors affecting bikeability. There is an added benefit of allowing comparisions of scores across regions too, which would allow us to formulate practical conclusions regarding infrastructure improvements and policy recommendations to promote cycling in Singapore. 

To build the Index, the following factors were chosen based on existing literatures' methodology and avaliability of data: 

<img src="Pictures/index_factors.png" width="600">

## Technical Data Processing 

1) Converted Digital Elevation Terrain Elevation data to Slope map of Singapore, then aggregated by subzones in Singapore

<img src="Pictures/slope_gif.gif" width="600">

2) Manually geolocating weather stations in Singapore, then interpolate the Precipitation values to cover whole of Singapore and finally aggregating to subzones

<img src="Pictures/precipitation_gif.gif" width="600">

3) Manually geolocating weather stations in Singapore, then interpolate the temperature values to cover whole of Singapore and finally aggregating to subzones

<img src="Pictures/temperature_gif.gif" width="600">

## Results 




## QY's role in the group project
I mainly handled the raster data processing and maps calculations/visualizations for the project. 

This was done at a time when I did not know how to code, so the most advanced skill I had was to figure out how to do raster processing on ESRI ArcGIS (because in school we were mostly taught how to deal with vector data). 

## Key technical skills
- Raster data processing: Slope calculations from Digital Elevation Terrain Raster data, Zonal Statistics
- Vector data processing: Interpolation (of rainfall and temperature from weather stations in Singapore)

## And Finally...
All good projects are done with the help of awesome-r teammates, so here is a shoutout to my fellow project mates back then @ Amanda Lim, Charis Tan, Ho Yihan and Hu Huidi!

### References 
