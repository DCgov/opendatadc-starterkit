# Getting Started with Open Data DC APIs

Welcome, Application Developers! We are very happy that you’re considering building with [Open Data DC](http://opendata.dc.gov). Our goal is for this site to be your platform for developing apps around DC’s freely available, machine readable data.

## How much of an intro do you need?

### Wait… I don’t know what an API is
[What is an API? In English, please.](https://medium.freecodecamp.com/what-is-an-api-in-english-please-b880a3214a82#.vyfqh1v6h]) from [freeCodeCamp](https://medium.freeCodeCamp.com)

### I’m new to opendata.dc.gov
[Opendata.dc.gov](http://opendata.dc.gov) is DC government's Open Data site. It runs on the Esri Open Data platform. [Here is the help for Esri Open Data](http://doc.arcgis.com/en/open-data/consumer/find-data.htm), to help you get comfortable and refer to later, when you're an expert

### I know what I’m doing - quickstart, please
Here is a quick walk-through on the basic workflow for discovering data and adding it to an app.

- **Step 1: Find the Data** 
Just think of a keyword and enter it in the search box. Suggested keyword searches will appear as you begin typing. DC tags its layers with words we think will match your expected results. 

![Open Data DC Searchbox](/help/images/opendatadc-search.png)

- **Step 2: Explore Data** 
Each data layer in the catalog comes with a brief description that helps give context. You will also see a publication date and boxes identifying attribute fields within the data. The Data tab at the top will show a preview of table. 

![Open Data DC Explore Data](/help/images/opendatadc-explore-data.png)

- **Step 3: Dive into the APIs**
The District of Columbia provides APIs and web services that empower you to create applications for fun, education, reporting, or business. The API Explorer tab at the top is where you can begin setting parameters and trying them out. 

![Open Data DC Explore APIs](/help/images/opendatadc-explore-api.png)

- **Step 4: Spin up API URLs**
In the details page of every data layer are three drop down menus. One of which contains a selection of pre-written URLs for the full dataset. Just copy and paste your chosen API into your application, or send it to your developer team. 

![Open Data DC Get APIs](/help/images/opendatadc-get-api.png)

![Open Data DC Get APIs](/help/images/opendatadc-get-api-2.png)

- **Finally: Put it all Together and Build** 

Use live from the opendata URL, or download as a snapshot. Either way, you can work with these APIs in any framework or tool that accepts geojson, csv, OGC WMS, and/or Esri json/geoservice.

To get a leg up, or just some ideas, use our open source starter kit ([Open Data DC Starter Kit](https://github.com/DCgov/opendata-dc-starterkit) featuring samples that show you how to use our APIs and data with ArcGIS, Mapbox, D3, and Leaflet. 

![esri logo](/help/images/logo-esri-50px.png)![mapbox logo](/help/images/logo-mapbox-50px.png)![D3 logo](/help/images/logo-d3-50px.png)![leaflet logo](/help/images/logo-leaflet-50px.png)![openstreetmap logo](/help/images/logo-osm-50px.png)![jquery logo](/help/images/logo-jquery-50px.png)![dojo logo](/help/images/logo-dojo-50px.png)

See something missing in the above technologies? Suggest it [by creating an issue](/../../issues), or [contribute your own sample](../CONTRIBUTING.md).

>![github](/help/images/logo-github.png) [DC.gov on GitHub](https://github.com/DCgov)

<br><br>
## FAQ

### Is a bulk API available?

All data is available for bulk download as csv. Unfortunately, there is not easy way to chunk the csv files for easier download. To get the direct link to the CSV, just copy the URL for the geojson and replace .geojson with .csv, e.g.

[http://opendata.dc.gov...80ecec9_2.**geojson**](https://opendata.arcgis.com/datasets/f2e1c2ef9eb44f2899f4a310a80ecec9_2.geojson) >> [http://opendata.dc.gov...80ecec9_2.**csv**](https://opendata.arcgis.com/datasets/f2e1c2ef9eb44f2899f4a310a80ecec9_2.csv)

<br>

### What is the difference between geojson and Esri json?

The short answer: both are valid json representations of earth-based geometries and the information attatched ot them. Geojson is more widely used in open source projects, while esri json is mostly used in the widely distributed Esri products. However, it’s important to note that more and more esri products are outputting geojson, and accepting geojson inputs. The [geojson specification](http://geojson.org/geojson-spec.html) is actually not bad reading for a document of this sort. But if you want something more lively, try Tom MacWright’s [More than you ever wanted to know about geojson](http://www.macwright.org/2015/03/23/geojson-second-bite.html). And, [here is the Esri json documentation](http://resources.arcgis.com/en/help/rest/apiref/geometry.html) 

>![github](/help/images/logo-github.png) Esri provides [some open source tools to work between the two formats](https://github.com/Esri/geojson-utils). While you’re there check out [Esri's other open source projects](https://github.com/Esri) 

<br>

### Who do I contact with questions, comments and concerns? 
This repo is maintained by the OCTO Data Team under the [DC Chief Data Officer](https://octo.dc.gov/blog/meet-chief-data-officer-barney-krucoff). For best response, email us at [data@dc.gov](mailto:data@dc.gov?subject=Open%20Data%20DC%20Starter%20Kit) and feel free to tweet us [@opendataDC](https://twitter.com/opendatadc).
