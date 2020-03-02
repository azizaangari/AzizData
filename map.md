<!DOCTYPE html>
<html>
  <head>
    <title>Give me a name!</title>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta charset="utf-8">
    <style>
      /* Always set the map height explicitly to define the size of the div
       * element that contains the map. */
      #map {
        height: 100%;
      }
      /* Optional: Makes the sample page fill the window. */
      html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      }
    </style>
  </head>
  <body>
    <div id="map"></div>
    <script>
      function initMap() {
        // Styles a map in custom mode.
        var map = new google.maps.Map(document.getElementById('map'), {
          center: {lat: 40.4583498, lng: -80.079528},  // Setting the center to Pittsburgh, change as you like
          zoom: 15,  // Setting a zoom scale for Pittsburgh
          styles:    // Add JSON from Map Style Wizard below this line... 

// ..and here's the end of JSON from Style Wizard          
        });
      }
// Don't forget your API Key below vv
    </script>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDmHU3ic4mGTO-CyGydlANBVQu3LzEWe-c&callback=initMap"
    async defer></script>
  </body>
</html>


https://maps.googleapis.com/maps/api/staticmap?key=AIzaSyDmHU3ic4mGTO-CyGydlANBVQu3LzEWe-c=41.30723891996383,-113.58925545405997&zoom=5&format=png&maptype=roadmap&style=element:geometry%7Ccolor:0x98a280&style=element:labels.text.fill%7Ccolor:0x523735&style=element:labels.text.stroke%7Ccolor:0xf5f1e6&style=feature:administrative%7Celement:geometry.stroke%7Ccolor:0xc9b2a6&style=feature:administrative.land_parcel%7Celement:geometry.stroke%7Ccolor:0xdcd2ff&style=feature:administrative.land_parcel%7Celement:labels.text.fill%7Ccolor:0x232226%7Cweight:1&style=feature:landscape.natural%7Celement:geometry%7Ccolor:0xdfd2ae%7Cvisibility:off&style=feature:poi%7Celement:geometry%7Ccolor:0xdfd2ae%7Cvisibility:off&style=feature:poi%7Celement:labels.text.fill%7Ccolor:0x000000&style=feature:poi.park%7Celement:geometry.fill%7Ccolor:0xa5b076&style=feature:poi.park%7Celement:labels.text.fill%7Ccolor:0x447530&style=feature:road%7Celement:geometry%7Ccolor:0xfffcf4%7Cvisibility:off&style=feature:road.arterial%7Celement:geometry%7Ccolor:0xfdfcf8&style=feature:road.highway%7Celement:geometry%7Ccolor:0xf8c967&style=feature:road.highway%7Celement:geometry.stroke%7Ccolor:0xe9bc62&style=feature:road.highway.controlled_access%7Celement:geometry%7Ccolor:0xe98d58&style=feature:road.highway.controlled_access%7Celement:geometry.stroke%7Ccolor:0xdb8555&style=feature:road.local%7Celement:labels.text.fill%7Ccolor:0xffddcd&style=feature:transit.line%7Celement:geometry%7Ccolor:0xdfd2ae%7Cvisibility:off&style=feature:transit.line%7Celement:labels.text.fill%7Ccolor:0x8f7d77%7Cvisibility:off&style=feature:transit.line%7Celement:labels.text.stroke%7Ccolor:0xebe3cd%7Cvisibility:off&style=feature:transit.station%7Celement:geometry%7Cvisibility:off&style=feature:water%7Celement:geometry.fill%7Ccolor:0xf2f2ef&style=feature:water%7Celement:labels.text.fill%7Ccolor:0x92997e&size=480x360
