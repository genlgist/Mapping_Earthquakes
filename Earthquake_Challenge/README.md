# Earthquake_Challenge

Regina Negrycz 
genglist@yahoo.com 
Module 13 Challenge 
Submitted 23 Jul 2021 
static/css/style.css
index.html
static/js/challenge_logic.js
README

# Overview
The goal of this project was to create a map having 3 layers and allowing the user to choose between the three map overlays and then choose either/or/both tectonic layers or earthquakes.

# Deliverable 1 

I added tectonic plate data as a second layer group and to the overlay object.  The tectonic plate data is passed to the geoJSON() layer and this layer adds color and width to the tectonic plate lines.

# Deliverable 2

I modified the challenge_logic script add dcolor for magnitudes less than 5, greater than 5 and greater than 6.  I turned each feature into a circleMarker on the map and styled each circle with styleInfo() function.  I created a pop up for the circle to display the magnitude and location of the earthquake.

# Deliverable 3

I added a third map tile layer and can toggle between the layers via the legend.


# Results

I added three layers to the map and was able to successfully search on each filter and combined filters.

