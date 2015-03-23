##Tabelle ”categories_distances” 

In dieser Tabelle wird festgelegt welche Entfernungen und Auflagengrößen geschossen werden.

####Schlüsselfelder

* [event_id]
* [class_id]
* [division_id]
* [round_id]

####Felder

* [distance]
* [face]

**Einschränkungen**

* Es ist nicht vorgesehen die Felder ”distance” und ”face” auszuwerten. Daher sind keine Abhängigkeiten innerhalb der Datenbank vorgesehen, welche die Eindeutigkeit der Inhalte garantieren.

###Beispiel

[event_id]|[class_id]|[division_id]|[round_id]|[distance]|[face]|Bemerkung
:--------:|:--------:|:-----------:|:--------:|:--------:|:----:|:--
1|1|1|1|90m|122cm|Recurve Men in der ersten Runde 90m 122cm-Auflage
1|1|1|2|70m|122cm|Recurve Men in der zweiten Runde 70m 122cm-Auflage
1|1|1|3|50m|80cm|Recurve Men in der dritten Runde 50m 80cm-Auflage
1|1|1|4|30m|80cm|Recurve Men in der vierten Runde 30m 80cm-Auflage
..|
2|1|1|0|70m|122cm|Recurve Men in allen runden Runde 70m 122cm-Auflage
..|
3|1|1|0|rot|x|Recurve Men in allen runden Runde vom Roten Pflock die Auflagen variieren (Feldbogen)

[event_id]:kapitel_07.md
[class_id]:kapitel_07.md
[division_id]:kapitel_07.md
[round_id]:kapitel_07.md
[distance]:kapitel_07.md
[face]:kapitel_07.md
