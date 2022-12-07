---
name: Balbinya's Wohnzimmer
area: Wald Fir Fe'lien
danger: low
date_first_visited: 478-06-23
date_last_visited: 478-06-27
---

## Beschreibung

Ein Wohnzimmer mitten im Wald, das durch eine geheime Formel geöffnet werden kann.

Teich, Sofa, Schlafzimmer, Sessel, Küche.


## NPCs
```dataview
table date_encounter as "Kennengelernt am"
from "NPCs"
where location.name = this.file.name
```

## Karte

```leaflet 
id: Feenferisches Nordland
image: [[Feenferisches Nordland.jpg]] 
height: 500px 
lat: 50 
long: 50 
minZoom: 1 
maxZoom: 10 
defaultZoom: 8
scale: 1 
```
