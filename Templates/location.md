---
name: <% tp.file.title %>
area: <% tp.file.cursor(0) %>
type:
danger: 
date_first_visited: 478-
date_last_visited: 478-
---

## Beschreibung



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
