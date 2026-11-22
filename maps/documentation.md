# Consultation instances with ChatGPT

## For Map 1:
### A. MAP INITIALISATION
* I asked how to format headings and create colour swatches for the legend to go in a separate div container from that for the map.
* I asked about the CSS syntax to specify the style for my map and legend.

### D. POPUPS
* I asked how to specify a popup for a polygon feature, instead of the point features used in the lecture.
* It also noted that I needed to supply map.on statements with listeners in addition to declaring hoverDA() and leaveDA().
* I asked how to make the setText two lines. It suggested to use .setHTML instead of .setText.


## For Map 2:
### From A. MAP INITIALISATION
* I didn't know how to add a label to seaLevelNumberEntry.

### From B. STYLING
* I didn't know how to create a choropleth style so I specified that I have a geojson file where one property is 'population'.
* I didn't know how to create a class for one specific value. ChatGPT said to use 'case'.

### From C. ADDING SOURCES AND LAYERS
* I didn't know a PMTiles protocol needed to be registered before being able to display the .pmtiles file.
* in the first map.addLayer block, I didn't know 'stroke' should instead be 'fill-outline-color'.

### From D. POPUPS
* I asked how to configure a click listener to listen for multiple layers. It said to put the layers in an array.

### From E. CONFIGURING showDEMButton:

