# geos472-group-map
For final project with Uku, Ira, Michelle.
## DEM files
Downloaded from https://catalogue.data.gov.bc.ca/dataset/digital-elevation-model-for-british-columbia-cded-1-250-000

The relevant tiles: 92g01w, 02ew, 03ew, 06ew, 07ew, 08w, 10ew, 11e

## webMapData.geojson
Metro Vancouver CMACA, dissemination areas, population as of 2021 downloaded from Simply Analytics.
I then added elevation data from the DEMs to the shapefiles of DAs.

Properties:
* NAME: DAID and region
* population: # of residents in that DA
* elevation: majority of land in metres above mean sea level
* area_km2: area of that DA in sq km
* pop_density: # of residents per unit sq km
* pd_rounded: above but rounded to integer
