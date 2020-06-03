# Covid-19Visualizer
A series of python scripts to automate collection of Covid-19 data to produce a map and video of active cases.

The included scripts in this repository work with QGIS to automate parts of the production of a map of Covid-19 active cases in a time series spanning fromt he 31st of December 2019 to the current day.

The code reads from https://opendata.ecdc.europa.eu/covid19/casedistribution/csv, performs some data aggregation to get total cases, deaths and total cases from two weeks ago, in order to calculate active cases.

The scripts include:
  
  - Get Covid-19 data
  - Process data for totals
  - Join Data to Country Centroid Shapefile
  - Refactor Attribute Fields and Load a layer style
  
These scripts work with QGIS, and the resultant project file can be rendered into atime series map with either the Time Manager Plugin, or the native temporal vector layer support that the current development version of QGIS supports (as of May 2020).
  
