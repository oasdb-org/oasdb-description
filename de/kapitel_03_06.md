##Tabelle ”club_teams”

Ein ”Club-Team” ist eine Gruppe von Einzelstartern, deren Ergebnisse addiert und als Mannschaftsergebnis gezählt wird. (siehe [sub:Mannschaft])

Die Einträge in dieser Tabelle stellen auf Datenbank-Ebene sicher, dass die Einzelstarter eindeutig einem ”Club-Team” zugeordnet sind. Die korrekte Kategorie- und Vereinszuordnung der Einzelnen lässt sich auf dieser Grundlage prüfen.

####Schüsselfelder

* [event_id]
* [club_team_id]

####Felder

* [title_short]
* [title]
* [association_id]
* [class_id]
* [division_id]

###Beispiel

[event_id]|[club_team_id]|[title_short]|[title]|[association_id]|[class_id]|[division_id]|Bemerkung
:--------:|:------------:|:-----------:|:-----:|:--------------:|:--------:|:-----------:|:------
2|1|BSC 1|Bogensportclub Team 1|10|U|R|BSC (siehe [associations]) stellt eine gemischte Recurve
2|2|BSC 2|Bogensportclub Team 2|10|U|C|und eine gemischte Compound-Mannschaft
2|3|BSV|Bogensportverein|12|U|R|BSV hat nur eine Recurve-Mannschaft


[association_id]:kapitel_07_a.md
[class_id]:kapitel_07_c.md
[club_team_id]:kapitel_07_c.md
[division_id]:kapitel_07_d.md
[event_id]:kapitel_07_e.md
[title]:kapitel_07_t.md
[title_short]:kapitel_07_t.md

[associations]:kapitel_03_01.md
