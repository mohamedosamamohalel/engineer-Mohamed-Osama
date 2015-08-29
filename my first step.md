<!DOCTYPE HTML>
<html> <head> <title>My first step</title>
<style tybe="text/css"> 
.credits {font-style: italic; }
body { padding: 20 px; font-family: arial, verdana, sans-serif; background: cyan; }
h1{ text-line: center; color: yellow; font-family: algerian; background: grey; font-size:300%; padding: 25px;}
h2,h3{color: green; font-family: italic; background-color: #eeeeee; font-size:150%; text-shadow: 2px 2px 7px;}
img {
width: 350px;
height:300px;}
#map { width: 500px; height: 400px;}
</style>
<script src="https://maps.googleapis.com/maps/api/js"></script>
    <script>
      function initialize() {
        var mappyramids = document.getElementById('map');
        var mapOptions = {
          center: new google.maps.LatLng(29.977296, 31.132496),
          zoom: 15,
          mapTypeId: google.maps.MapTypeId.SATELLITE
        }
        var map = new google.maps.Map(mappyramids, mapOptions)
      }
      google.maps.event.addDomListener(window, 'load', initialize);
    </script>
</head>
<body> <h1>Mohamed Osama</h1>

<p>I'm twenty years old, from Assuit.</p>
<p>I'm studying at <i>the Fucalty of Engineering</i>.</p>
<p>I love reading, playing chess and learning new things.</p>
<p> <img src="http://static.communitytable.parade.com/wp-content/uploads/2013/09/live-life-like-game-of-chess-ftr.jpg" alt="chess" title="chess" align="center" /> </p>
<h2>My favorite website</h2>
<p><ul> <li><a href="http://www.wikihow.com">how to do anything</a></li> </ul> </p>
<p class="credits">Thank you....</p>
<h3>my favorite place</h3>
<div id="map"></div> <p> the Pyramids </p>
</body></html>
