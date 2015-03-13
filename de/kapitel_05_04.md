##Tabelle "matches_teams_results"

Es ist bekannt auf welcher Ebene die Ausscheidungsrunde gestartet wird. (siehe [Match])
Somit können vor Wettkampfbeginn festgelegt werden
* nötige Anzahl der 
* nötigen Paarungen

Da sich die Besetzung der Startplätze erst im Wettkampfgeschehen ergibt (siehe [Match]) müssen/können die Positionen erst im laufenden Betrieb besetzt werden.

####Schlüsselfelder
* event_id
* session_id
* round_id
* pair_id
* team_id

####Felder
* setpoints
* matchpoints

###Beispiel "Liga"
event_id|session_id|round_id|pair_id|team_id|setpoints|matchpoints|Beschreibung
:------:|:--------:|:------:|:-----:|:-----:|:-------:|:---------:|:-----------
1|1|1|1|005|0|0|Am ersten Spieltag verliert im ersten Match "Team A (id 5)"
1|1|1|1|004|6|2|"Team B (id 4)" mit "0:6". "Team B" erhält somit 2 Matchpunkte
1|1|1|...|...|...|...|
1|1|2|3|005|6|2|Im zweiten Match trifft "Team A (id 5)" auf
1|1|2|3|007|2|0|"Team D (id 7)" und gewinnt mit 6:2. "Team A" erhält somit 2 Matchpunkte

###Beispiel "Compound - kummulierendes System"


[Match]: kapitel_08_match.md "Match-Runden"
