
---
name: <% tp.file.title %>
race: <% tp.file.cursor(0) %>
class:
appearance:
ethos:
date_encounter: 478-
---
### Metadaten
location:: [[]]
trade:: [[]]

## Beschreibung


## Quests
```dataview
table date_created_ig as "Angenommen", date_finisehd_ig as "Abgeschlossen", danger as Gefahr, priority as "!"
from "Quests"
where client = this.file.name
sort priority desc
```
