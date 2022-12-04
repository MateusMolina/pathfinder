---
name: <% tp.file.title %>
area: 
danger: 
date_visited: 478-
---

## Beschreibung



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
