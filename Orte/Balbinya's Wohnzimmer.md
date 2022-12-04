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

## Quests
```dataview
table date_created_ig as "Angenommen", date_finished_ig as "Abgeschlossen"
from "Quests"
where location = this.file.name
```
