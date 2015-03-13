##Tabelle ”sessions”

Diese Tabelle beinhaltet die Durchgänge eines Wettkampfes. 

Als Durchgang wird ein Abschnitt in einem Wettkampf angesehen der ohne Änderung der Wettkampfform durchgeführt wird und nachdem es ein End- oder ein Zwischenergebnis gibt. Es wird davon ausgegangen, dass ein Durchgang an einem Ort stattfindet.

Gründe für die Einrichtung von mehreren Durchgängen können sein:

* Es gibt mehr Starter als Startplätze. Die Starter, die in einer Kategorie um eine Plazierung kämpfen treten im gleichen Durchgang an.
* Es gibt Termine "Hauptwettkampf","Vorschießen" und/oder "Nachschießen".
* Der Wettkampf findet in mehreren Phasen statt. Es gibt "Qualifikationsrunde", "Ausscheidungsrunde", "Finale".

Die Felder [first_target_number] und [last_target_number] erlauben es mehrere "sessions" gleichzeitig auf einem Platz stattfinden zu lassen. Das können beispielsweise Vorentscheidungen in Gruppen sein, wobei jede Gruppe als "session" behandelt wird.

####Schlüsselfelder

* event_id
* session_id

####Felder

* title_short
* title
* venue
* first_target_number
* last_target_number
* starter_per_target
* rules