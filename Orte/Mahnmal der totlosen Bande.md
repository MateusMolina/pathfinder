---
name: Mahnmal der totlosen Bande
area: 
danger: medium-high
date_first_visited: 478-
date_last_visited: 478-
---

## Beschreibung
Ein Ort, an dem irgendetwas schreckliches vorgefallen ist!


## NPCs
```dataview
table date_encounter as "Kennengelernt am"
from "NPCs"
where location = this.file.name
```

## Quests
```dataview
table date_created_ig as "Angenommen", date_finished_ig as "Abgeschlossen"
from "Quests"
where location = this.file.name
```
