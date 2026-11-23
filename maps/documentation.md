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
* I didn't know how to add a label to seaLevelSlider. It told me to add the <p> </p> section and the <span> </span> above seaLevelSlider.
* Since I wanted the text in affectedCount to change, it told me to use <p> and <span> instead of <button>.

### From B. STYLING
* I didn't know how to create a choropleth style so I specified that I have a geojson file where one property is 'population'.
* I didn't know how to create a class for one specific value. ChatGPT said to use 'case'.

### From C. ADDING SOURCES AND LAYERS
* I didn't know a PMTiles protocol needed to be registered before being able to display the .pmtiles file.
* In the first map.addLayer block, I didn't know 'stroke' should instead be 'fill-outline-color'.
* The 'DAs-highlighted' layer is from asking how to show the highlighted DAs (see: G.)
* I didn't know that accessing a .pmtiles file needed a pmtiles:// starter.

### From D. POPUPS
* I asked how to configure a click listener to listen for multiple layers. It said to put the layers in an array.

### From F. CONFIGURING SLIDER
* I asked what is the event name of a move in the slider. It said it is 'change' and added that the keyword 'this.' will store that value.

### From G. HOW MANY PEOPLE AFFECTED?
* I didn't know you can't use a url as a feature collection to iterate through in a for-loop; it said to declare DAs globally first (hence the earliest 'let DAs').
* I asked how to add features to a dataset. It said to add .setData and the keywords for the other parameters to the source I am adding to.
* I asked how to sum the 'population' property of each feature pushed to DAs.

