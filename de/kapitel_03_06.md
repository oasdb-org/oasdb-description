##Tabelle ”club_teams”

Ein ”Club-Team” ist eine Gruppe von Einzelstartern, deren Ergebnisse addiert und als Mannschaftsergebnis gezählt wird. (siehe [sub:Mannschaft])

Die Einträge in dieser Tabelle stellen auf Datenbank-Ebene sicher, dass die Einzelstarter eindeutig einem ”Club-Team” zugeordnet sind. Die korrekte Kategorie- und Vereinszuordnung der Einzelnen lässt sich auf dieser Grundlage prüfen.

**Schüsselfelder**

* event_id (Fremdschlüssel [sub:Tabelle-”events”])
* club_team_id ([sub:team_id])

**Felder**

* title_short 
* title
* association_id
* category
