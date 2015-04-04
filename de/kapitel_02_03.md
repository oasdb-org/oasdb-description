##Tabelle ”sessions”

Diese Tabelle beinhaltet die Durchgänge eines Wettkampfes. 

Als Durchgang wird ein Abschnitt in einem Wettkampf angesehen der ohne Änderung der Wettkampfform durchgeführt wird und nachdem es ein End- oder ein Zwischenergebnis gibt. Es wird davon ausgegangen, dass ein Durchgang an einem Ort stattfindet.

Gründe für die Einrichtung von mehreren Durchgängen können sein:

* Es gibt mehr Starter als Startplätze. Die Starter, die in einer Kategorie um eine Plazierung kämpfen treten im gleichen Durchgang an.
* Es gibt Termine "Hauptwettkampf","Vorschießen" und/oder "Nachschießen".
* Der Wettkampf findet in mehreren Phasen statt. Es gibt "Qualifikationsrunde", "Ausscheidungsrunde", "Finale".

Die Felder [first_target_number] und [last_target_number] erlauben es mehrere "sessions" gleichzeitig auf einem Platz stattfinden zu lassen. Das können beispielsweise Vorentscheidungen in Gruppen sein, wobei jede Gruppe als "session" behandelt wird.

Im Feld [session_type] wird angegeben welche Art von Wettkampf in diesem Durchgang durchgeführt wird. Dies ist an dieser Stelle nötig, da sich diese Auswahl auf die Nutzung nachfolgenden Tabellen und Feldern auswirkt.

####Schlüsselfelder

* [event_id]
* [session_id]

####Felder

* [title_short]
* [title]
* [venue]
* [first_target_number]
* [last_target_number]
* [starter_per_target]
* [session_type]
* [rounds_per_session]
* [ends_per_round]
* [arrows_per_end]


###Beispiel
[event_id]|[session_id]|[title_short]|[title]|[venue]|[first_target_number]|[last_target_number]|[starter_per_target]|[session_type]|[rounds_per_session]|[ends_per_round]|[arrows_per_end]|Beschreibung
:--------:|:----------:|:-----------:|:-----:|:-----:|:-------------------:|:------------------:|:------------------:|:------------:|:------------------:|:--------------:|:--------------:|:--
1|1|vor2015|Vorschießen 720'er - Runde|Sportplatz|5|7|4|IKR|2|6|6|Vorschießen für die Meisterschaft mit drei Scheiben
1|2|VM 2015|Vereinsmeisterschaft 720'er - Runde|Sportplatz|1|10|4|IKR|2|6|6|Vereinsmeisterschaft Meisterschaft mit 10 Scheiben
--|
2|2|Aus-R|Ausscheidungsrunde Recurve (Viertel- bis Goldfinale)|Sportplatz|2|5|2|IMP|4|5|6|Ausscheidungsrunde Recurve auf Scheibe 2 bis 5
2|2|Aus-C|Ausscheidungsrunde Compound (Viertel- bis Goldfinale)|Sportplatz|6|9|2|IMR|4|3|6|Ausscheidungsrunde Compound auf Scheibe 6 bis 9


[session_type]: kapitel_07_s.md#session_type
[first_target_number]: kapitel_07_n.md#number_of_targets
[last_target_number]: kapitel_07_n.md#number_of_targets

[title_short]: kapitel_07.md
[title]: kapitel_07.md
[venue]: kapitel_07.md
[starter_per_target]: kapitel_07.md
[rounds_per_session]: kapitel_07.md
[ends_per_round]: kapitel_07.md
[arrows_per_end]: kapitel_07.md
[event_id]: kapitel_07.md
[session_id]: kapitel_07.md
