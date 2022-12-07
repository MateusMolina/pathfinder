---
name: Dunkelstieg
area: 
type: Höhle
danger: low
date_first_visited: 478-06-26
date_last_visited: 478-06-27
---

## Beschreibung

Ein verzweigtes Höhlensystem. Hier gibt es Kristalle, die wir auf Reaktion auf Schall untersucht haben.


## NPCs
```dataview
table date_encounter as "Kennengelernt am"
from "NPCs"
where location = this.file.name
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