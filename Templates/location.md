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
