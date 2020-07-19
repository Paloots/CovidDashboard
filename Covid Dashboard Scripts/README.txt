
Authors : Petrus Loots (18358802); Ruan Pretorius (20270828)


The Project has two main sections, namely, the Data Manipulation and the Dashboard 

* Data Manipulation NoteBook

This notebook contains all the code that downloads and scrapes all the needed data for the Dashboard.
This notebook also merges all the data sets into usable CSV files for later use. 
If you run the Data Manipulation file with an empty folder named Data and an empty folder named Merged Data in the same 
directory as the RMD, it will download all the data and manipulate it so that the Dashboard has new data and that you don't have to 
share the datasets that will be out of date within 24 hours. This way the dashboard can update with the latest data each time by running the script.

*  Dashboard 

The Dashboard has two aspects, the RMD and the HTML. The HTML is a self contained application based on the data from the Data Manipulation Output.
To Create a new version of the HTML one simply need to download the newest data with the Data Manipulation RMD and then 
Knit the Dashboard RMD into a HTML. 

The Dashboard uses R's Flex web framework. It compiles the R markdown into Java Script code into the HTML.
Most of the plots are made using ggplot2 and Plotly making them interactive when hovering over axis data. 
The Maps are created and made interactive by using Leaflet. 
 
