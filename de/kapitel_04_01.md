##Tabelle ”positions_individuals”

In dieser Tabelle werden die Starter in einer Qualifikationsphase auf Ihre Startplätze verteilt.

Auch wenn davon ausgegangen werden kann, dass ein Starter in der Qualifikationsphase vom gleichen Startplatz schießt wird für jede Runde ein Startplatz eingetragen.

Im nächsten und letzten Schritt werden die Ergebnisse pro Starter eingetragen. Es werden nur für die Starter Ergebnisse erfasst, die auch einen Startplatz haben.

Diese Herangehensweise sellt sicher, dass nur für gültige Starter ein Ergebnis erfasst werden kann. 



####Schlüsselfelder
* event_id
* session_id
* round_id
* position

####Felder
* participant_id
* individual_id


###Beispiel

event_id|session_id|round_id|participant_id|individual_id|position|Beschreibung
:------:|:--------:|:------:|:------------:|:-----------:|:------:|:-----------
1|1|1|230|1|10A|Starter 230.1 hat in der ersten Runde im ersten Durchgang Startplatz 10A
1|1|2|230|1|10A|Starter 230.1 hat in der zweiten Runde im ersten Durchgang Startplatz 10A
1|2|1|230|2|3A|Starter 230 tritt im zweiten Durchgang mit einem anderen Bogen an und hat in der ersten Runde Startplatz 3A
1|2|1|101|1|3B|Neben ihm steht Starter 101 der nur in einer Kategorie startet



[results_individuals]: kapitel_05_01.md
