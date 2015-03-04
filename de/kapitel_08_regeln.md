##Regeln

Für jeden Wettkampf gelten Regeln, welche die Einträge in der Datenbank betreffen. Diese Regeln lassen sich in den Ordnungen nachlesen.

* Welche Sortierung und Gruppierung wird für die Ermittlung der Platzierungen verwendet?
* Wonach wird bei Ringgleichheit differenziert ("X/10", "10/9", "6/5", ...)?
* Welche Regeln gelten für das Aufstellen einer Matchrunde?
* Nach welchen Regeln vergleichen sich die Mannschaften bei einem Liga-Wettkampf?
* ...

Da eine Umsetzung des Regelwerkes mit Mitteln der elektronischen Datenverarbeitung angestrebt wird stellt sich die Frage "Wie und wo hinterlege ich diese Regeln ?".

* Man könnte dies in der/den Anwendung(en) integrieren, die auf diese Datenbank zugreift.
* Man könnte in der Datenbank für jede Regel ein Felder anlegen.
* Man könnte in der Datenbank ein allgemeines Feld "Regeln" anlegen in der die Regeln in einer bestimmten elektronisch auswertbaren Form geklärt werden.

Ich entscheide mich in meinen weiteren Ausführungen für die dritte Variante. Diese ist zwar sehr komplex aber dafür bietet sie die größte Flexibilität und Transparenz.

Es wird ein Textfeld eingerichtet. In diesem Feld werden die Regeln in einer XML-Struktur abgelegt. Es gibt sowohl auf der Ebene "event" aus auch auf der Ebene "session" ein solches Feld.

