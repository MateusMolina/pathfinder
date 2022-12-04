```dataview
table client as Mandant, location as Ort, date_ig_created as Datum, date_ig_finished as Fertiggestellt, priority as "!"
from "Quests"
where file.name != "#Quests"
sort priority DESC
```
