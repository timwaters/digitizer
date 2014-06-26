Historic Map Digitizer
====

This is a vector editor / manual digitizer for historical maps.

![Screenshot of NYPL Map Digitizer](https://github.com/timwaters/digitizer/raw/master/NYPL_screenshot.png "Screenshot of NYPL Map Digitizer")

It's mainly written with GeoEXT, Mapfish, OpenLayers.

Demo
====

A demo of the interface can be found running on Heroku at <a href="http://digitizer.herokuapp.com">http://digitizer.herokuapp.com</a>

![Screenshot of NYPL Map Digitizer](https://github.com/timwaters/digitizer/raw/master/Heroku_screenshot.png "Screenshot of Demo")

Features
====
* Polygon, Line, Point editing
* Multiple layers
* Customisable schemas
* WFS compatability with Geoserver
* Customisabale WMS / Tile layers
* Dynamic drop down select boxes for types and subtypes
* Lists of all features
* Lists of modified features. This is subdivided into added, edited, deleted sections
* Clicking on a feature in the list hightlights and zooms to it on the map



Note
====

Note that this requires Geoserver running a WFS (or WFS-V) instance. I'm sure it's possible to configure it to work with other WFS servers. More information about configuring this with a warper interface can be found here: http://code.mapwarper.net/wiki/DigitizerSetup

Origin
====
Developed by Tim Waters with Topomancy LLC and the New York Public Library

This came from the Mapwarper repository - and now exists as a Sinatra application for demo purposes.
The Digitizer is going to be removed from the main mapwarper code base.
