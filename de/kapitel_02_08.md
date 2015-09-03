##Tabelle ”rounds” 

Die Tabelle beinhaltet die Runden, die geschossen werden können. Eine Erläuterung des ist [hier](kapitel_08_runde.md) zu finden.

In dieser Tabelle wird nur ein Name für die Runden festgelegt. Es ist daher möglich, dass eine in dieser Tabelle festgelegte Runde in mehreren Durchgängen ([sessions]) eingebunden wird.

Um dies verdeutlichen sollen hier einige Runden beispielhaft benannt werden.

* **Erste Entfernung** (Anwendung bei 1440'er-Runde)
* **Unbekannte Entfernung** (Anwendung bei Feldbogenrunde)
* **1** und **2** (Anwendung bei 720'er Runde bei der zwei Mal die gleiche Entfernung geschossen wird.)
* **Viertelfinale** (Anwendung in einer Finalrunde)
* **Match 1** (Anwendung bei einem Ligawettkampf)

Die Festlegung der tatsächlichen Entferungen und Scheibenauflagen geschieht in der Tabelle [categories_rounds].

####Schlüsselfelder

* [event_id]
* [round_id]

####Felder

* [label_short]
* [label]

###Beispiel

event_id|round_id|label_short|label|Bemerkung
:------:|:------:|:---------:|:----|:--------
1|1|1|Runde 1|720' Runde 1
1|2|2|Runde 2|720' Runde 2
..|
2|1|1|1. Entfernung|1440'er Runde
2|2|2|2. Entfernung|1440'er Runde
2|3|3|3. Entfernung|1440'er Runde
2|4|4|4. Entfernung|1440'er Runde
..|
3|1|unb.|Unbekannte Entfernungen|Feldbogenrunde
3|2|bek.|Bekannte Entfernungen|Feldbogenrunde
..|
4|1|4tel|Viertelfinale|Ausscheidungsrunde mit Finale
4|2|halb|Halbfinale|Ausscheidungsrunde mit Finale
4|3|br.Fin|Bronze-Finale|Ausscheidungsrunde mit Finale
4|4|finale|Gold-Finale|Ausscheidungsrunde mit Finale

[categories_rounds]:kapitel_02_09.md
[sessions]:kapitel_02_03.md

[event_id]:kapitel_07_e.md#event_id
[round_id]:kapitel_07_r.md#round_id
[label_short]:kapitel_07_l.md#label_short
[label]:kapitel_07_l.md#label
