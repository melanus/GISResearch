# GISResearch
Undergraduate research done to be able to plot points and traverse through them - Used for warrants on phones


Program: plotpoints.html
	Program designed to take a geojson file and plot the points on a map, be able to traverse through them, and read in the meta data from the CSV file. 

Author: Matthew Lanus
	mlanus@nd.edu

Date: April, 2016

University of Notre Dame, Computer Science and Engineering Department 

Program still in development. 
Future plans:
	Better layout of the site
		Create actual site with server - not just local document
	Parse date on data and plot accordingly
	Greater automation for converting files
	
Necessary Files: 
	plotpoints3.html
	
	icon.css (if you want it to look good - otherwise, very clunky looking)
	
	at least one geojson file
	
	jquery-2.1.1.min.js executable
		Found here: https://jquery.com/download/     - also included the executable



INSTRUCTIONS:

	1. Make folder for contents of webpage

	2. Place this program/website into folder

	3a.For Excel/CSV File
		1. Download csv of Excel file
		2. Go to http://mapbox.github.io/csv2geojson/ and convert the csv to geojson
		3. Copy the geojson data and save it into a file called points.geojson in the folder you have created (can be named differently, but will need to edit code nominally)
			- If different file name, go to line 86 and 223 and replace points.geojson with correct file name

	3b. For KMZ/KML files
		1. Go to http://converter.mygeodata.eu/#top
		2. Choose file to upload on the left and hit submit
		3. For Target vector format, select geojson (json)
		4. Download data and place into folder - call it points.geojson (can be named differently, but will need to edit code nominally)
			- If different file name, go to line 86 and 223 and replace points.geojson with correct file name

	4. Open the program (plotpoints.html) in the web browser of your choice 
	
	5. To change metadata, add in the text box on the webpage the headers of whichever columns you would like to include, serparated by commas (and no spaces). Once all the meta data that you want is listed, press submit
	
	6. Click each point to view the meta data
	
	7. To traverse through the list of points, click next and or previous
		To return to normal view, refresh the page (check the metadata to make sure the points are in correct order - order based on way file came in)


