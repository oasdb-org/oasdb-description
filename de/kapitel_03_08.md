##Tabelle „teammembers“

Diese Tabelle kommt zum Einsatz wenn Wettbewerbe durchgeführt werden, bei denen das Mannschaftsergebnis im Vordergrund steht.

Ausgehend von den Tabellen [participants] und [teams] werden die Mannschaften zusammengestellt, und klassifiziert. 

**Besonderheit „Liga-Mannschaft“**

Die Besonderheit bei Ligamannschaften ist, dass einer Mannschaft mehr als drei Mitglieder zugeordnet werden können. Es wird im Wettkampf entschieden, wer in welchem Match zum Einsatz kommt. 

**Besonderheit „3D-Runde“**

Eine Mannschaft in einer 3D Runde besteht aus einem Compound, einem Instinktivbogen und einem Langbogen-Teilnehmer. Es ist somit nötig zu vermerken in welcher Kategorie jedes einzelne Mannschaftsmitglied startet.

####Schüsselfelder

* [event_id]
* [team_id]
* [participant_id]

####Felder

* [division_id]

###Beispiel 

[event_id]|[team_id]|[participant_id]|[division_id]|Bemerkung
:--------:|:-------:|:--------------:|:-----------:|:----
2|1|1|<null>|Team 1 - Teilnehmer 1 (Bogenart ist in [teams] geklärt)
2|1|2|<null>|Team 1 - Teilnehmer 2 
2|1|3|<null>|Team 1 - Teilnehmer 3
...|
2|2|1|<null>|Team 2 - Teilnehmer 1 (Bogenart ist in [teams] geklärt)
2|2|2|<null>|Team 2 - Teilnehmer 2 
2|2|3|<null>|Team 2 - Teilnehmer 3
...|
3|1|1|C|Team 1 - Teilnehmer 1 - Compound
3|1|2|I|Team 1 - Teilnehmer 2 - Instinktiv
3|1|3|L|Team 1 - Teilnehmer 3 - Longbow

[event_id]:kapitel_07_e.md
[division_id]:kapitel_07_d.md
[participant_id]:kapitel_07_p.md
[team_id]:kapitel_07_t.md

[participants]: kapitel_03_03.md
[teams]: kapitel_03_07.md
