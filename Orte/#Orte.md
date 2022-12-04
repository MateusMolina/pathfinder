```dataview
table area as Gebiet, danger as Gefahr, date_visited as "Besucht am"
from "Orte"
where file.name != "#Orte"
sort date_last_visited
```
