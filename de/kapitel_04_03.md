##Tabelle "matches_individuals_positions"
Es ist bekannt auf welcher Ebene die Ausscheidungsrunde gestartet wird. (siehe [Match])
Somit können vor Wettkampfbeginn festgelegt werden
* nötige Anzahl der 
* nötigen Paarungen

Da sich die Besetzung der Startplätze erst im Wettkampfgeschehen ergibt (siehe [Match]) müssen/können die Positionen erst im laufenden Betrieb besetzt werden.

**Schlüsselfelder**
* event_id
* session_id
* round_id
* pair_id
* participant_id
* invividual_id

**Felder**
* position

###Beispiel Finalrunde

event_id|session_id|round_id|pair_id|participant_id|individual_id|position|Beschreibung
:------:|:--------:|:------:|:-----:|:------------:|:-----------:|:------:|:-----------
1|3|1|1|230|2|1A|Nach zwei Qualifikationsrunden tritt Starter 230.2 im ersten Match (Viertelfinale) gegen
1|3|1|1|101|1|1B|Starter 101.1 auf Schreibe 1 an. "230.2" steht links "101.1" steht rechts
1|3|1|2|...|...|...|Zweites Paar
1|3|1|3|...|...|...|Drittes Paar
1|3|1|4|090|1|6a|Als viertes Paar treffen auf Scheibe 6 Starter 090.1
1|3|1|4|132|1|6b|und Starter 132.1 aufeinander
1|3|2|...|...|...|...|Halbfinale
1|3|3|...|...|...|...|Bronze-Finale
1|3|4|1|230|2|5|Im Gold-Finale treffen "230.2" (auf Scheibe 5)
1|3|4|1|132|1|6|und Starter 132.1 aufeinander

[Match]: kapitel_08_match.md "Match-Runden"
