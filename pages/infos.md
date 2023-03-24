---
layout: page
title: "Informations"
teaser: ""
permalink: "/infos/"
leaflet: true
header:
  image_fullwidth: joueur-echecs.jpg
---
### Comment venir ?
L'Open d'Échecs de Pion Pacé est organisé à la MJC de Pacé, 4 avenue Charles le
Goffic à Pacé. 

<div id="map" style="height: 180px;"></div>
<script>
  var lat = 48.148864698663104;
  var lon = -1.77454737712369;

  var map = L.map('map').setView([lat, lon], 13);
 
  L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
  }).addTo(map);
  
  var marker = L.marker([lat, lon]).addTo(map);

  marker.bindPopup("<b>MJC Pion Pacé</b><br>4 av. Charles le Goffic, 35740 Pacé").openPopup(); 
</script>

#### En bus 
Depuis Rennes, prendre la ligne 65 ou la ligne 77 du bus Star jusqu'au centre
ville (arrêt Carré Dumaine ou Duchesse Anne). La MJC se trouve à moins de 10
minutes à pieds.

#### En voiture
Depuis la N12, prendre la sortie Pacé centre puis suivre les panneaux vers le 
centre ville. Un fléchage sera installé pour vous guider jusque la MJC.

