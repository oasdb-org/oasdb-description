##label
*einzeilger Text*

Das Feld "label" beinhaltet eine Bezeichnung. In der Regel ist "label" die Hauptinformation in dem Datensatz.

Im Gegensatz dazu beinhaltet "title" eine Überschrift. Im gleichen und/oder untergeordneten Datensätzen folgen Informationen, die sich auf diese Überschrift beziehen.

##label_sort
*einzeiliger Text - max 10 Zeichen*

Kurzform von "lable".

##labels
*(Blob - text/xml)*

Das Feld enthält die Bezeichnungen der Datenbankfelder in einer XML-Struktur. Das Attribut "encoding" ist in jedem Fall mit zu führen um zu gewährleisten, dass Umlaute korrekt ausgelesen werden.

Die Bezeichnungen der in der Datenbank verwendeten Felder können auch als XML-Tag verwendet werden. 

Über das Attribut "lang" ist es möglich mehrere Sprachen zu hinterlegen.

<pre><code>&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;labels&gt;
	&lt;<i>name des feldes</i> lang=&quot;<i>sprache</i> [de|en|...]&quot;&gt;
		&lt;long&gt;[lange Bezeichnung für das Feld]&lt;/long&gt;
		&lt;short&gt;[kurze Bezeichnung für das Feld]&lt;/short&gt;
	&lt;/<i>name des feldes</i>&gt;
	...
&lt;/labels&gt;</code></pre>

##limit
*(positive Ganzzahl)*

Diese Feld kommt zum Einsatz, wenn es in einer Kategorie eine Beschränkung bei der Zulassung gibt. Hier wird die Ringzahl hinterlegt, die nötig ist um am Wettkampf teilnehmen zu können.
