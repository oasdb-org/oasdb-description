##Tabelle "matches_teams_positions"
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
* position

###Beispiel "Liga"
event_id|session_id|round_id|pair_id|team_id|position|Beschreibung
:------:|:--------:|:------:|:-----:|:-----:|:------:|:-----------
1|1|1|1|005|1|Am ersten Spieltag tritt in der ersten Match "Team A (id 5)" auf Scheibe 1 an
1|1|1|1|004|2|und kämpft gegen "Team B (id 4)"
1|1|1|2|002|3|"Team C (id 2)" auf Scheibe 3 gegen
1|1|1|2|007|4|"Team D (id 7)" auf Scheibe 4 gegen
1|1|1|...|...|...|
1|1|2|1|003|1|Im zweiten Match steht "Team 3" auf Scheibe 1
1|1|2|1|005|2|und kämpft gegen "Team 5" auf Scheibe 2
1|1|...|...|...|...|
1|2|1|1|002|1|Am zweiten Spieltag wurde neu gemischt und "Team C (id 2)" liegt auf fünfter Position
1|2|1|1|005|2|und trifft auf den vierten in der Wertung "Team A (id 5)"

[Match]: kapitel_08_match.md "Match-Runden"
