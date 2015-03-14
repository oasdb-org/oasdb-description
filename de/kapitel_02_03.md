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

###Beispiel
<table>
<tr>
  <td>[event_id]</td>
  <td>[session_id]</td>
  <td>[title_short]</td>
  <td>[title]</td>
  <td>[venue]</td>
  <td>[first_target_number]</td>
  <td>[last_target_number]</td>
  <td>[starter_per_target]</td>
  <td>[session_type]</td>
  <td>Beschreibung</td>
</tr>
<tr>
  <td>1</td>
  <td>1</td>
  <td>vor</td>
  <td>Vorschießen 720'er - Runde</td>
  <td>Sportplatz</td>
  <td>5</td>
  <td>7</td>
  <td>4</td>
  <td>IKR</td>
  <td>Vorschießen für die Meisterschaft mit 10 Scheiben </td>
</tr>
<tr>
  <td>1</td>
  <td>2</td>
  <td>720'er</td>
  <td>720'er - Runde</td>
  <td>Sportplatz</td>
  <td>1</td>
  <td>10</td>
  <td>4</td>
  <td>IKR</td>
  <td>Meisterschaft mit 10 Scheiben </td>
</tr>
<tr>
  <td colspan="9">&nbsp;</td>
</tr>
<tr>
  <td>2</td>
  <td>1</td>
  <td>Quali</td>
  <td>720'er - Runde</td>
  <td>Sportplatz</td>
  <td>1</td>
  <td>10</td>
  <td>4</td>
  <td>IKR</td>
  <td>Qualifikationsphase auf zehn Scheiben</td>
</tr>
<tr>
  <td>2</td>
  <td>2</td>
  <td>Aus-R</td>
  <td>Ausscheidungsrunde Recurve (Viertel- bis Goldfinale)</td>
  <td>Sportplatz</td>
  <td>2</td>
  <td>5</td>
  <td>2</td>
  <td>IMP</td>
  <td>Ausscheidungsrunde Recurve auf Scheibe 2 bis 5</td>
</tr>
<tr>
  <td>2</td>
  <td>3</td>
  <td>Aus-C</td>
  <td>Ausscheidungsrunde Compound (Viertel- bis Goldfinale)</td>
  <td>Sportplatz</td>
  <td>6</td>
  <td>9</td>
  <td>2</td>
  <td>IMR</td>
  <td>Ausscheidungsrunde Compound auf Scheibe 6 bis 9</td>
</tr>
</table>

[session_type]: kapitel_07_s.md#session_type
[first_target_number]: kapitel_07_n.md#number_of_targets
[last_target_number]: kapitel_07_n.md#number_of_targets
