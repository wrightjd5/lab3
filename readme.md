# Flat Top Lookout Tower Via Green Knob Trail

#### Route map

---

This is a route map leading from Green Knob Trailhead, through Hebron Falls Trailhead, and ends at Flat Top Lookout Point. There are a notable stops and scenic views along the way, such as Trout Lake and the Blue Ridge Parkway. The route is not entirely a traditional trail, and takes a shortcut through a suburb to get you over to Flat Top Lookout. The route line and point markers were created in google maps and then turned into a gpx file using an open source tool [(Maps to GPX)](https://mapstogpx.com/). These data were then edited and converted into a GeoJSON file on [geojson.io](http://geojson.io/#map=2/20.0/0.0) and loaded as a variable in javascript. It was then displayed using [Leaflet](https://leafletjs.com/) JavaScript library through two functions. The first pulled the "LineString" geometry type from the GeoJSON and the second pulled the "Point" geometry type from the GeoJSON. They were both then displayed on the map. 