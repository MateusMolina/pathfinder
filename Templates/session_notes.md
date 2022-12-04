---
date_ig: 478- 
date_rl: <% tp.date.now("YYYY-MM-DD") %>
duration: 
---

## Zusammenfassung
- 

## Quests
```dataview
table client as Mandant, location as Ort, status as Status, priority as "!"
from "Quests"
where date_created_rl = this.date_rl
or date_finished_rl = this.date_rl
```

## Loot
- 