##Tabelle ”countries”

Diese Tabelle beinhaltet Regionen, welche den Teilnehmern zugeordnet werden können. Dies können Städte, Kreise, Länder, Kontinente sein.

Sollte es nötig sein darzustellen, dass eine Region Teil einer anderen Region ist (hierarchische Struktur) dann kann das Feld ”part_of” genutzt werden. In diesem Feld wird die ”country_id” der übergeordneten Region eingetragen. 

Alle Regionen/Länder werden in einer Tabelle gespeichert. Die hierarchische Ordnung ergibt sich aus der internen Verknüpfung der Datensätze über das Feld ”part_of”. Auf Grund dieses Mechanismus ist die maximale Tiefe der hierarchischen Ordnung nicht vorgegeben oder eingeschränkt.

Dem Teilnehmer wird nur der Eintrag mit der kleinsten Hierachiestufe zugewiesen. Alle anderen ergeben sich aus den hinterlegten Verknüpfungen.

####Schlüsselfelder

* [event_id]
* [country_id]

####Felder

* [title_short]
* [title]
* [part_of]

###Beispiele

[event_id]|[country_id]|[title_short]|[title]|[part_of]|Bemerkung
:--------:|:--------------:|:------------|:------|:-------:|:---------
1|1|BR|Brandenburg|<null>|Event 1 ist eine Kreismeisterschaft bei der nur Teilnehmer aus dem Land antreten
...|...|...|...|...|
2|1|DE|Deutschland|<null>|Event 2 ist eine Deutsche Meisterschaft
2|10|BR|Brandenburg|1|Land Brandenburg 
2|11|SN|Sachsen|1|Land Sachsen
...|...|...|...|...|
3|1|EU|Europe|<null>|Europa
3|2|DE|Deutschland|1|Deutschland
3|3|PL|Polen|1|Polen
3|4|BRB|Land Brandenburg|2|(Wenn man es ganz detailiert haben will)


[event_id]:kapitel_07_e.md#event_id
[country_id]:kapitel_07_c.md#country_id
[title_short]:kapitel_07_t.md#title_short
[title]:kapitel_07_t.md#title
[part_of]:kapitel_07_p.md#part_of
