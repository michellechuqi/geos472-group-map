# geos472-group-map
For final project with Uku, Ira, Michelle.

## DEM files
Downloaded from https://catalogue.data.gov.bc.ca/dataset/digital-elevation-model-for-british-columbia-cded-1-250-000

The relevant tiles that cover all of Metro Vancouver: 92g01w, 02ew, 03ew, 06ew, 07ew, 08w, 10ew, 11e

## webMapData.geojson
Metro Vancouver CMACA, dissemination areas, population as of 2021 downloaded from Simply Analytics. Simply Analytics uses data from the 2021 Canada Census.
I then added elevation data from the DEMs to the shapefiles of DAs.

**Properties**:
* NAME: DAID and region
* population: # of residents in that DA
* elevation: majority of land in metres above mean sea level
* area_km2: area of that DA in sq km
* pop_density: # of residents per unit sq km
* pd_rounded: above but rounded to integer

## maps/map1-code.html
To view map: https://michellechuqi.github.io/geos472-group-map/maps/map1-code.html

It is a map of all dissemination areas in Metro Vancouver. User can zoom and pan around. They can hover over a DA and see its name and location, the population, and the # of people per 1 sq km. The choropleth values are by population density - user can refer to the legend for classification details.

## maps/map2-code.html
To view map: https://michellechuqi.github.io/geos472-group-map/maps/map2-code.html

It is a map map of all dissemination areas in Metro Vancouver. User can zoom and pan around. They can hover over a DA and see its name and location, the elevation, and the population. The choropleth values are elevation values in metres above mean sea level - user can refer to the legend for further details.
 

## Exploratory (aspatial) data analysis:
https://michellechuqi.github.io/geos472-group-map/aspatial-EDA/eda.html
