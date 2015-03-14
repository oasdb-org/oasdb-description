##Tabelle ”positions_individuals”

In dieser Tabelle werden die Starter Ihre Startplätze verteilt. 

Das Feld [round_id] wird mit geführt. So besteht die Möglichkeit zu planen und/oder zu dokumentieren, dass Starter in den verscheidenen Runden verscheidenen Startplatz einnehmen. Wird das Feld mit "0 (null)" belegt, so nimmt der Starter in allen Runden des Durchganges [session_id] diesen Startplatz ein.

Im nächsten und letzten Schritt werden die Ergebnisse pro Starter eingetragen. Es werden nur für die Starter Ergebnisse erfasst, die auch einen Startplatz haben.

Diese Herangehensweise sellt sicher, dass nur für gültige Starter ein Ergebnis erfasst werden kann. 

####Schlüsselfelder
* [event_id]
* [session_id]
* [round_id]
* [position]

####Felder
* [participant_id]
* [individual_id]

###Beispiel

event_id|session_id|round_id|position|participant_id|individual_id|Beschreibung
:------:|:--------:|:------:|:------:|:------------:|:-----------:|:-----------
1|1|0|10A|230|1|Starter 230.1 hat in beiden Runde im ersten Durchgang Startplatz 10A
1|2|0|3A|230|2|Der gleiche Starter tritt im zweiten Durchgang mit einem anderen Bogen an erhält die Startnummer 123.2 und hat Startplatz 3A
1|2|0|3B|101|1|Neben ihm steht Starter 101.1 der nur in einer Kategorie startet
1|3|1|1A|101|1|Starter 101.1 steht in der ersten Runde im dritten Druchgang auf Platz 1A
1|3|2|10C|101|1|in der zweiten Runde wechselelt er nach 10C *(warum auch immer)*



[results_individuals]: kapitel_05_01.md
