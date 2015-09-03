##Tabelle ”events”

Als "event" wird eine Veranstaltung angesehen, bei der es am Ende Platzierungen in verscheidenen Kategorien gibt. Es ist möglich, dass die Veranstaltung in aus mehreren Durchgängen "[sessions]" (*z.B. "Qualifikation, "Ausscheidungsrunde", ...*) besteht.

Die Tabelle "events" enthält nur grundlegende Informationen über die Veranstaltung. Details über ”Durchgänge”, ”Zeitplan innerhalb der Durchgänge”, ”Zusätzliche Texte, Hinweise, Bilder” werden in separaten Tabellen eingetragen.

Angaben über Austragungsort "venue" wurden bewusst in die Tabelle ”[sessions]” ausgelagert. Werden mehrere Austragungsorte festgelegt, so lassen sich diese in einer Liste unter Angabe des Durchganges auflisten.

Der zeiltlich Ablauf einers Durchganges ist in "[sessions_timetable]" geregelt.

Um eine klare Benennung der Felder zu gewährleisten werden die umgangssprachlichen Namen der Datenbankfelder im Feld [labels] mitgeführt. Hier ist die Benennung der Felder "tiebreaker_1", "tiebreaker_2" und "tiebreaker_3" von besonderer Bedeutung. 

Abhängig von der Art des Wettkampfes steht
* "tiebreaker_1" für "10'er", "10er+Xer", "5er"
* "tiebreaker_2" für "9'er", "Xer", "6er"
* "tiebreaker_3" steht für "Gewinner Stechen" oder "Münzwurf"

####Schlüsselfelder

* [event_id]

####Felder

* [title_short]
* [title]
* [foreign_key_divider]
* [frontend_labels]
* [organizer]
* [rules]
* [registration_until]
* [timestamp_created]
* [timestamp_modified]

[sessions]: kapitel_02_03.md
[frontend_labels]: kapitel_07_f.md#frontend_labels
[event_id]: kapitel_07_e.md#event_id
[title_short]: kapitel_07_t.md#title
[title]: kapitel_07_t.md#title
[foreign_key_divider]: kapitel_07_f.md
[sessions_parts]:kapitel_02_04.md
[registration_until]:kapitel_07_r.md#registration_until
