
Authors : Petrus Loots (18358802); Ruan Pretorius (20270828)


To launch the site: Open the Index.html file in any web browser. The pages for this site are sorted in chronological order.

The Project has two main sections, namely, the Data Download and Manipulation ,
and the Covid-19 Twitter Dashboard 


* Data Download and Manipulation NoteBook

This notebook contains all the code that downloads and scrapes all the needed Tweets from Twitter for the Dashboard
and saves the Tweets data to an external CSV file. This notebook also contains the code that cleans the twitter data 
to the form where the dataframe is ready for analysis.


*  Dashboard 

The Dashboard has four aspects, an Index, Topic Model, Sentiment and Word Network RMD files and their related HTML files. Each HTML is a self contained application based on the data from the RMD files output
and each HTML is linked together to form the complete application. The structure of the Dashboard has been designed in order to function in the same manner as a website.


The Dashboard uses R's Flex web framework. It compiles the R markdown into Java Script and HTML code.
Most of the plots are made using ggplot2 and Plotly making them interactive when hovering over axis data. 
