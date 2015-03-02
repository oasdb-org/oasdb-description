##Tabelle „individuals“

Ausgehend von der Tabelle ”participants” werden hier die Sportler hinterlegt, die als Einzelstarter am Wettkampf teilnehmen. Es werden noch keine Startplätze vergeben.

Die allgemeinen persönlichen Daten eines Teilnehmers (Tabelle ”participants”) werden um die Angaben ergänzt, die seine sportliche Teilnahme am Wettkampf angehen. Es ist somit ausgeschlossen, dass es Schreibfehler im Namen gibt, wenn der Teilnehmer in mehreren Rollen am Wettkampf teilnimmt.

Ein Starter hat über den gesamten Wettkamf eine (oder mehrere) eindeutige Starter-ID. Diese Start-ID setzt sich zusammen aus ”Wettkampfnummer”-”Teilnehmernummer”-”Starternummer”. Es wurde bewusst darauf verzichtet die Felder ”class_id”, ”division_id”, ”session_id” als Schlüsselfelder auszunehmen. Dies wäre aus Sicht der Datenbank zwar eindeutig, jedoch führ es dazu, dass sich die Starter-ID ändert sobald die Altersklasse korrigiert werden muss oder der Starter in einem anderen oder in zwei Durchgängen antritt.

Durch diese Festlegungen sind folgende Fälle realisierbar sind: 

* Ein Sportler kann im mehreren Kategorien am Wettkampf teilnehmen.
* Der Sportler kann mehrfach in der gleichen Kategorie starten. Zum Beispiel in der Qualifikation, im Finale und einer zweiten Chance.
* Ein Teilnehmer hilft beim ersten Durchgang bei der Durchführung des Wettkampfes und ist im zweiten Durchgang selbst Teilnehmer.

Die Struktur der Datenbank lässt aber auch widersprüchliche oder sinnlose Einträge zu. Dies muss von einer Anwendung geprüft werden. Diese Einträge können sein:

* Ein Teilnehmer startet in allen Kategorien.
* Ein Teilnehmer startet in zwei Druchgängen in der gleichen Kategorie.

**Schlüsselfelder**

* event_id (Fremdschlüssel [sub:Tabelle-”events”])
* participant_id (Fremdschlüssel [sub:Tabelle-”participants”])
* individual_id ()

**Felder Kategorie**

* class_id (Fremdschlüssel [sub:Tabelle-”categories”])
* division_id (Fremdschlüssel [sub:Tabelle-”categories”])

