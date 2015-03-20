##labels
*(Blob - text/xml)*

Das Feld enthält die Bezeichnungen der Datenbankfelder in einer XML-Struktur. 

Die Bezeichnungen der in der Datenbank verwendeten Felder können auch als XML-Tag verwendet werden. 

Über das Attribut "lang" ist es möglich mehrere Sprachen zu hinterlegen.

<pre><code>&lt;labels&gt;
	&lt;<i>name des feldes</i> lang=&quot;&lt;sprache [de|en|...] &gt;&quot;&gt;
		&lt;long&gt;[lange bezeichnung für das Feld]&lt;/long&gt;
		&lt;short&gt;[kurze bezeichnung für das Feld]&lt;/short&gt;
	&lt;/<i>name des feldes</i>&gt;
	...
&lt;/labels&gt;</code></pre>

##limit
*(positive Ganzzahl)*
