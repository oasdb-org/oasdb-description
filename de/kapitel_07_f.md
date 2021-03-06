## fee
Startgebühr (ohne Währung)

## foreign_key_divider

Feld enthält nur ein Zeichen. Werden externe Schlüsselfelder importiert, so ist dieses Zeichen der Trenner zwischen den Teilen des Schlüssels.

## frontend_labels
*(Blob - text/xml)*

Das Feld enthält die umgangssprachlichen Bezeichnungen der Datenbankfelder. Die Bezeichnungen sind in einer XML-Struktur abgelegt. Das Attribut "encoding" ist in jedem Fall mit zu führen um zu gewährleisten, dass Umlaute korrekt ausgelesen werden.

Die Bezeichnungen der in der Datenbank verwendeten Felder können auch als XML-Tag verwendet werden. 

Über das Attribut "lang" ist es möglich mehrere Sprachen zu hinterlegen. Das Attribut "version='short'" zeigt an, dass es sich um die Kurzversion handelt.

<pre><code>&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;labels&gt;
	&lt;<i>name des feldes</i> lang=&quot;<i>sprache</i> [de|en|...]&quot; version=&quot;[short]&quot;&gt;
		Bezeichnung für das Feld
	&lt;/<i>name des feldes</i>&gt;
	...
&lt;/labels&gt;</code></pre>
