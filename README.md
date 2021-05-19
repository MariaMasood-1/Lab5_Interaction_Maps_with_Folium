# Lab 5: Interaction Maps with Folium

The goal of this lab is to create a map that shows the location of starbucks on the basemap of LA. This lab employs the Folium python library, which builds on a common web mapping javascript library called Leaflet to build interactive maps. During the process of creating a map, this lab covers the deatils on the difference between a good and bad choropleth map. The first choropleth map used zip codes to generate the locations of starbuch on a map but the problem with the map is that it shows a small number of Starbuck's spread out over a large area (as it matches the zip code for the location index) and those areas are just north of zip codes that are greyed out because they contain no data. The finer map uses the longitude and the latitude value of the starbuck's to create the choropleth map which is much more efficient and easy to understand. <br>

## **Libraries used:** <BR>
  
**-Folium:** Folium is a Python wrapper for Leaflet. js which is a leading open-source JavaScript library for plotting interactive maps. It has the power of Leaflet. js and the simplicity of Python, which makes it an excellent tool for plotting maps. <br>

**JSON:** JSON (JavaScript Object Notation), specified by RFC 7159 and by ECMA-404, is a lightweight data interchange format inspired by JavaScript object literal syntax (although it is not a strict subset of JavaScript 1 ). json exposes an API familiar to users of the standard library marshal and pickle modules. <br>

**Pandas:** Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. 


