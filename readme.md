# A Haunted Tour of the High Country
## About this project
This project is an interactive web map showcasing a route taking you to various haunted or mysterious locations around the High Country. Location data and point descriptions provided by [Explore Boone](https://www.exploreboone.com/blog/post/nc-high-country-hauntings/).




I used Google Maps to plan my route, which I then exported into a GPX file using [mapstogpx](mapstogpx.com). I then took the exported gpx file and used [geojson.io](geojson.io) to tweak the route, add points that correspond to the locations from Explore Boone, add descriptions, and adjust symbology.




This web map was created with [Leaflet](https://leafletjs.com/), with javascript used to load and style the route and point features. This map utilizes leaflet's bindTooltip() function to provide descriptions for each stop when moused over.


I used CartoDB for my basemap, specifically the DarkMatter basemap.  I used ghost emojis for my points, and the font [Creepster](fonts.google.com) for my title to fit the spooky theme.
