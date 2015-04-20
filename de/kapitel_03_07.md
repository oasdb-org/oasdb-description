##Tabelle ”teams” 

Die Tabelle wird dann benötigt, wenn Wettkämpfe ausgetragen werden, bei denen nur Mannschaftsergebnisse und keine Einzelergebnisse gewertet werden. (siehe [mannschaften])

Die Mannschaften werden beschrieben (Verein, Kategorie) und die einzelnen Mitglieder in der Tabelle [team_members] aufgeführt.

*Mitglieder einer Mannschaft werden nicht zuätzlich in der Tabelle ”individuals” aufgeführt.*

####Schüsselfelder

* [event_id]
* [team_id]

####Felder

* [title_short]
* [title]
* [class_id]
* [division_id]

###Beispiel
[event_id]|[team_id]|[title_short]|[title]|[class_id]|[division_id]|Bemerkung
:--------:|:-------:|:-----------:|:-----:|:--------:|:-----------:|:--
2|1|BSC1|Bogensportclub|1*(M)*|1*(R)*|BSC stellt eine Herren-Recurve-Mannschaft 
2|2|BSC2|Bogensportclub|2*(W)*|1*(R)*|und eine Damen-Recurve-Mannschaft 
2|2|BSV|Bogensportverein|2*(W)*|1*(R)*|BSV nur eine Damen-Recurve-Mannschaft 
...|
3|1|BSV|Bogensportverein|1*(U)*|1*(U)*|BSV stellt bei einem 3D-Wettkampf eine gemischte Mannschaft (Compound, Instinktiv, Longbow)



[Mannschaften]: kapitel_08_mannschaft.md
[team_members]: kapitel_03_08.md

[class_id]:kapitel_07_c.md
[division_id]:kapitel_07_d.md
[event_id]:kapitel_07_e.md
[team_id]:kapitel_07_t.md
[title_short]:kapitel_07_t.md
[title]:kapitel_07_t.md
