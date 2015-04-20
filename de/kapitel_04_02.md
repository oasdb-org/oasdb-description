##Tabelle ”positions_teams"

In dieser Tabelle werden die Starter in einer Qualifikationsphase auf Ihre Startplätze verteilt.

Es wird davon ausgegangen, dass ein Starter über den gesammten Durchgang ("session") den gleichen Startplatz einnimmt. Bei Wettkämpfen im Parcours-Bereich heißt das, dass er in der gleichen Gruppe bleibt.

Daher findet keine weitere Differenzierung in den Schlüsselfelder statt. Eine Feld "round_id" wird nicht in eingefügt.

####Schlüsselfelder
* [event_id]
* [session_id]
* [round_id]
* [position]

####Felder
* [team_id]

###Beispiel
[event_id]|[session_id]|[round_id]|[position]|[team_id]|Bemerkung
:--------:|:----------:|:--------:|:--------:|:-------:|:--------
1|1|1|10A|1|


[event_id]:kapitel_07_e.md#event_id
[session_id]:kapitel_07_s.md#session_id
[round_id]:kapitel_07_r.md#round_id
[position]:kapitel_07_p.md#position
[team_id]:kapitel_07_t.md#team_id
