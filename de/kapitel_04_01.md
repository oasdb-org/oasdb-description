##Tabelle ”positions_individuals”

In dieser Tabelle werden die Starter Ihre Startplätze verteilt. 

Das Feld [round_id] wird mit geführt. So besteht die Möglichkeit zu planen und/oder zu dokumentieren, dass Starter in den verscheidenen Runden verscheidenen Startplatz einnehmen. Wird das Feld mit "0 (null)" belegt, so nimmt der Starter in allen Runden des Durchganges [session_id] diesen Startplatz ein.

Das Feld [pair] kommt nur bei Match-Runden zum Einsatz.

Die Tabelle stellt in den Schlüsselfeldern die Startplätze bereit, denen die Starter zugeordnet werden. Über die Schlüsselfelder ist sichergestellt, dass ein Startplatz nur ein im Durchgang (und Runde) vergeben werden kann.

Beispiel

> Ein Starter meldet sich mit einem Compound und einem Recurve an. Ihm werden die Startplätze 2A und 2D zugewiesen. Er schießt den Recurve auf 2A und den Compound auf 2D.

> *Zugegeben:* Für die anderen Scheibenpartner und den Kampfrichter ist dies eine besondere Herausforderung zu beobachten ob der Starter immer den richtigen Bogen nutzt.

####Schlüsselfelder
* [event_id]
* [session_id]
* [round_id]
* [position]

####Felder
* [participant_id]
* [individual_id]
* [pair]

###Beispiel

event_id|session_id|round_id|position|participant_id|individual_id|pair|Beschreibung
:------:|:--------:|:------:|:------:|:------------:|:-----------:|:--:|:-----------
1|1|0|10A|230|1|0|Starter 230.1 hat in beiden Runde im ersten Durchgang Startplatz 10A
1|2|0|3A|230|2|0|Der gleiche Starter tritt im zweiten Durchgang mit einem anderen Bogen an erhält die Startnummer 123.2 und hat Startplatz 3A
1|2|0|3B|101|1|0|Neben ihm steht Starter 101.1 der nur in einer Kategorie startet
1|3|1|1A|101|1|0|Starter 101.1 steht in der ersten Runde im dritten Druchgang auf Platz 1A
1|3|2|10C|101|1|0|in der zweiten Runde wechselelt er nach 10C *(warum auch immer)*
...|
1|5|1|10A|101|1|1|Starter "101.1" steht in der Ausschreidungsrunde auf Platz 10A und
1|5|1|10B|230|2|1|schießt gegen "230.2" der Auf Platz 10B steht.


[results_individuals]: kapitel_05_01.md
[pair]: kapitel_07_p.md#pair
[participant_id]: kapitel_07_p.md#participant_id
[individual_id]: kapitel_07_i.md#individual_id
[event_id]: kapitel_07_e.md#event_id
[session_id]: kapitel_07_s.md#session_id
[round_id]: kapitel_07_r.md#round_id
[position]: kapitel_07_p.md#position
