# opendatadc-starterkit
This repo is a collection of samples designed to demonstrate how developers can use the json-based APIs found at [Open Data DC](http://opendata.dc.gov) to build data-centric applications. It is managed by DC Government staff members of Chief Data Officer's team.

[Explore Live Demos](http://open.dc.gov/opendatadc-starterkit/)

About the Samples
----------
The samples... 
- require only basic web development skills.
- are easily hacked by simply changing data sources, titles, and making other minor configuration changes.
- have an understated but pleasing look-and-feel.
- show how you can consume data on [Open Data DC](http://opendata.dc.gov) in lots of clients: esri, D3, mapbox, leaflet, google maps

Table of Contents
----------
Number| Name | Description | Technologies
------------  | ------------ | ------------- | -------------
1|[dcopendata_atmlocations_arcgis](http://open.dc.gov/opendatadc-starterkit/dcopendata_atmlocations_arcgis.html)|Simple clustering using ArcGIS JS API|<a href="https://dojotoolkit.org/" target="_blank">Dojo</a>, <a href="https://developers.arcgis.com/javascript/" target="_blank">ArcGIS JS API</a>
2|[dcopendata_bikeshare_mapbox](http://open.dc.gov/opendatadc-starterkit/dcopendata_bikeshare_mapbox.html)|Uses pin to location and simple buffer to reveal points in range, includes seach by location, 'my location', and drag and drop/click anywhere responses|<a href="https://www.mapbox.com/mapbox-gl-js/api/" target="_blank">Mapbox GL JS</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>
3|[dcopendata_buildingpermits_mapbox](http://open.dc.gov/opendatadc-starterkit/dcopendata_buildingpermits_mapbox.html)|Simple clustering example with slider to display monthly datasets using Mapbox|<a href="https://www.mapbox.com/mapbox-gl-js/api/" target="_blank">Mapbox GL JS</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>, <a href="https://d3js.org/" target="_blank">D3</a>
4|[dcopendata_crime_collapsibletree_mapbox](http://open.dc.gov/opendatadc-starterkit/dcopendata_crime_collapsibletree_mapbox.html)|Displays crime data using dendrogram using mapbox| <a href="https://www.mapbox.com/mapbox-gl-js/api/" target="_blank">Mapbox GL JS</a>, <a href="https://d3js.org/" target="_blank">D3</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>
5|[dcopendata_crime_treemap_d3]( http://open.dc.gov/opendatadc-starterkit/dcopendata_crime_treemap_d3.html)|Displays crime data as a treemap using d3|<a href="https://d3js.org/" target="_blank">D3</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>|
6|[dcopendata_income_choropleth_google](http://open.dc.gov/opendatadc-starterkit/dcopendata_income_choropleth_google.html)| Load values and display them with graduated colors with additional popups on scroll over/click using Google Maps JS API| <a href="https://developers.google.com/maps/documentation/javascript/" target="_blank">Google Maps JS API</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>
7|[dcopendata_school_buffer_arcgis](http://open.dc.gov/opendatadc-starterkit/dcopendata_school_buffer_arcgis.html)|Simple example of geometry engine buffering using ArcGIS JavaScript API 4.X|<a href="https://dojotoolkit.org/" target="_blank">Dojo</a>, <a href="https://developers.arcgis.com/javascript/" target="_blank">ArcGIS JS API</a>
8|[dcopendata_school_mapbox](http://open.dc.gov/opendatadc-starterkit/dcopendata_school_mapbox.html)|Simple example of how to create side layout next to map and add interaction between data list item and map|<a href="https://www.mapbox.com/mapbox.js/api/v3.0.1/" target="_blank">Mapbox JS</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>
9|[dcopendata_ward_leaflet](http://open.dc.gov/opendatadc-starterkit/dcopendata_ward_leaflet.html)|Simple example of loading in a basic data set using open source library|<a href="https://leafletjs.com/" target="_blank">Leaflet</a>, <a href="https://jquery.com/" target="_blank">JQuery</a>

----------

Credits
----------
* [OpenStreetMap (OSM)](https://www.openstreetmap.org)
* [Esri for Developers](https://developers.arcgis.com/)
* [MapBox Developer Tools](https://www.mapbox.com/developers/)
* [Leaflet Tutorials](https://leafletjs.com/examples.html)
* [Google Maps API](https://developers.google.com/maps/)

Contributing
------------
See [CONTRIBUTING.md](../master/CONTRIBUTING.md)

License
----------
See [LICENSE.md](../master/LICENSE.md)

etc
----------
Other examples of interesting and effective uses of data on http://opendata.dc.gov:
- Temporal visualization, distance selection, and summarizing crime data using Esri tools https://github.com/ajturner/dc-crime 
