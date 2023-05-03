# LoadMultiPolygons using CSPro-JS API and Leaflet
 This is a basic example for loading multiple polygons in CSPro. Sometimes GeoJSON files coming from QGIS are not compliant to 
 the CSPro Map engine. It's why, among others, I implemented the function geojsonDataString() to display GeoJSON string and test 
 them on https://geojsonlint.com/. However, even after choosen one polygon, it's mandatory to refresh the view. This may be a limi-
 tation from the 7.7 CSPro-JS Api. Hopefully we will have a more robust and fully bidirectional CSPro-JS API in the next cut.
