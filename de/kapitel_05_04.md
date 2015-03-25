##Tabelle "matches_teams_results"

Es ist bekannt auf welcher Ebene die Ausscheidungsrunde gestartet wird. (siehe [Match])
Somit können vor Wettkampfbeginn festgelegt werden
* nötige Anzahl der 
* nötigen Paarungen

Da sich die Besetzung der Startplätze erst im Wettkampfgeschehen ergibt (siehe [Match]) müssen/können die Positionen erst im laufenden Betrieb besetzt werden.

####Schlüsselfelder
* [event_id]
* [session_id]
* [round_id]
* [pair_id]
* [team_id]

####Felder
* [score]
* [setpoints]
* [matchpoints]

###Beispiel "Liga"
event_id|session_id|round_id|pair_id|team_id|score|setpoints|matchpoints|Beschreibung
:------:|:--------:|:------:|:-----:|:-----:|:---:|:-------:|:---------:|:-----------
1|1|1|1|005|45|0|0|Am ersten Spieltag verliert im ersten Match "Team A (id 005)"
1|1|1|1|004|50|6|2|"Team B (id 004)" mit "0:6". "Team B" erhält somit 2 Matchpunkte
1|1|1|...|...|...|...|
1|1|2|3|005|53|6|2|Im zweiten Match trifft "Team A (id 005)" auf
1|1|2|3|007|50|2|0|"Team D (id 007)" und gewinnt mit 6:2. "Team A" erhält somit 2 Matchpunkte

###Beispiel "Compound - Match mit kummulierender Zählung"
*(Die "setpoints" werden nicht beachtet. Bei "kummulierender Zählung" werden die Ringe nach ...-Passen/Sets zur Bestimmung des Siegers herangezogen)*

event_id|session_id|round_id|pair_id|team_id|score|setpoints|matchpoints|Beschreibung
:------:|:--------:|:------:|:-----:|:-----:|:---:|:-------:|:---------:|:-----------
21|3|1|1|005|53|0|0|In der ersten Ausscheidungsrunde schießt Team A(id 005) 53 Ringe gegen"
21|3|1|1|004|55|0|2|"Team B (id 004)", dass 55 Ringe schießt. Damit holt "B" zwei Matchpunkte.

[event_id]:kapitel_07.md
[session_id]:kapitel_07.md
[round_id]:kapitel_07.md
[pair_id]:kapitel_07.md
[team_id]:kapitel_07.md
[score]:kapitel_07.md
[setpoints]:kapitel_07.md
[matchpoints]:kapitel_07.md


[Match]: kapitel_08_match.md "Match-Runden"
