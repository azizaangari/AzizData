Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@azizaangari 
OpenGlobe
/
portfolio
0
01
 Code Issues 0 Pull requests 0 Actions Projects 0 Wiki Security Insights
portfolio/sample_google_styling_wizard_template.html
@OpenGlobe OpenGlobe Create sample_google_styling_wizard_template.html
570b356 on Nov 4, 2019
39 lines (38 sloc)  1.19 KB
  
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
    <script src="https://maps.googleapis.com/maps/api/js?key=YOURAPIKEYHERE&callback=initMap"
    async defer></script>
  </body>
</html>
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
