## Tabelle ”events_information”

In der Tabelle werden zusätzliche Informationen zum Wettkampf gespeichert. 

Da Art und Umfang der Zusatzinformationen stark von der Anwendung abhängen und zudem von Wettkmapf zu Wettkampf unterscheidlich ist wurde entschieden diese nicht in der Tabelle "event" zu speichern.

Für jede Zusatzinformation wird eine neuer Datensatz eingerichtet. Neben der eigentlichen Information ist noch der Informationstyp und ein Kurztitel hinterlegt.

So ist es möglich Texte und Bilder zu hinterlegen.

**Schüsselfelder**

* [event_id]
* [information_id]

**Felder**

* [title]
* [content_type]
* [content]

###Beispiel
event_id|information_id|title|content_type|content
:------:|:------------:|:---------:|:----------:|:------
1|1|logo_01|image/jpeg|*Ein Bild*
1|2|anmerkungen|text/plain|Stargeld ist Reugeld. Sauberes Schuhwerk, ...
1|3|anmeldung|text/html|<b>Hinweise zur Anmeldung</b> <ul><li>"bis wann",</li><li> "bei wem", ...

[event_id]:kapitel_07_e.md#event_id
[information_id]:kapitel_07_i.md#information_id
[title]:kapitel_07_t.md#title
[content_type]:kapitel_07_c.md#content_type
[content]:kapitel_07_c.md#content
