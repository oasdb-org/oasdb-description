##Eindeutigkeit der Startnummern

###Einzelstarter
Die Startnummer der Einzelstarter setzt sich aus drei Teilen zusammen:
* event_id
* participant_id
* individual_id

Sie ist damit über den gesamten Wettkampf eindeutig und kann für den gesamten Wettkampf (*event*) gelten. Die Informationen über "Kategorie", "Startplatz", ... werden als Zusatzinformationen hinterlegt.

Die "individual_id" ist nötig, da es vorkommen kann, dass eine Person in mehreren Kategorien startet. 
>Die "individual_id" wird bewusst nicht durch "category_id" ersetzt. Stellt sich unmittelbar vor oder während des Wettkampfes heraus, dass der Teilnehmer falsch klassifiziert wurde, so würde sich die Startnummer ändern wenn er einer anderen Kategorie zugeordnet werden würde.

####Beispiel 1
* Wettkampf (event_id:12) 
  * startet die Person (participant_id:98) 
    * einmalig (individual_id:1) / Schreibweise mit Trenner: **12.98.1**

####Beispiel 2 (gleiche Datenbank wie Beispiel 1)
* Wettkampf (event_id:3) 
  * Person 1 (participant_id:2)
    * Kategorie 1 (individual_id:1) / Schreibweise mit Trenner: **03.02.1**
  * Person 2 (participant_id:32)
    * Kategorie 1 (individual_id:1) / Schreibweise mit Trenner: **03.32.1**
    * Kategorie 2 (individual_id:2) / Schreibweise mit Trenner: **03.32.2**

###Fazit
Das Aussehen der Startnummern ("mit oder ohne Trenner", "Führende Nullen", ...) sollte in der Datenbank geklärt werden um Fehldeutungen auf Ausdrucken und beim Enlesen der Daten zu vermeiden.
