##Tabelle ”events”

Die Tabelle ”events” enthält alle allgemeinen Informationen über den Wettkampf. 

Als "event" wird eine Veranstaltung angesehen, bei der es am Ende Platzierungen in verscheidenen Kategorien geben kann. Es ist möglich, dass die Veranstaltung in aus mehreren Durchgängen "sessions" (*z.B. "Qualifikation, "Ausscheidungsrunde", ...*) besteht.

Details über ”Durchgänge”, ”Zeitplan innerhalb der Durchgänge”, ”Zusätzliche Texte, Hinweise, Bilder” werden in separaten Tabellen eingetragen.

Angaben über Austragungsort "venue" wurden bewusst in die Tabelle ”session” ausgelagert. Werden mehrere Austragungsorte festgelegt, so lassen sich diese in einer Liste unter Angabe des Durchganges auflisten.

Da ein Durchgang aus mehreren Teilen bestehn kann ergibt sich der Zeitplan der Veranstaltung aus den Zeitangaben der Teile der Durchgänge "sessions_parts".

**Schlüsselfelder**

* event_id

**Felder**

* title_short
* title
* foreign_key_divider
* championship_id
