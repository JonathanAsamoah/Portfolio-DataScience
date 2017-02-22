# Wrangling OpenStreetMap Data

For this project data from [Open Street map](https://www.openstreetmap.org/#map=5/51.500/-0.100) is downloaded. The data comes in the xml format and gets wrangeled and than stored in a mongo db database.

Therfore, the data is inspected for inconsistend or false values, in the next step the data is cleaned and than transformed for storing in a MongoDB database.  

# Languages/Technologies

* Python 
  * xml
  * regex
* MongoDB

# Remarks

In this project the data the project is build on is not included in the repository. To download the data to the repository run the *Download the data* section once. After that the lines which call the download function can be comment out to prevent the code from downloading the data every time you run the code.

The python project contains a requirements.txt file. Which you can use to load the required libraries for the project using ``pip install -r requirements.txt``.

As database in this project MongoDB is used. To use the code parts related to MongoDB you have to install MongoDB. In doing so follow this [instructions](https://docs.mongodb.com/manual/installation/).

# Data

* [OpenStreetMap: Munich](http://overpass-api.de/api/map?bbox=11.4388,48.0593,11.6448,48.2507)

