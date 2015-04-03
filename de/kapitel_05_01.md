##Tabelle ”results_individuals”

####Schlüsselfelder
* [event_id]
* [session_id]
* [round_id]
* [participant_id]
* [individual_id]

####Felder
* [score]
* [tiebreaker_1]
* [tiebreaker_2]
* [tiebreaker_3]

###Beispiele "Feldbogen - Gleiche Ringzahl - 6'er entscheiden"
*(tiebreaker_1: "5'er+6'er" / tiebreaker_2: "6'er" / tiebreaker_3: "Stechen oder Los")*

Starter "123.1" hat die gleiche Ringzahl wie Starter "200.1". Die "5'er sind auch gleich. Starter "200.1" gewinnt, da er die höhere Anzahl an "6'er" in der zweiten Runde hat.

event_id|session_id|round_id|participant_id|individual_id|score|tiebreaker_1|tiebreaker_2|tiebreaker_3
:------:|:--------:|:------:|:------------:|:-----------:|:---:|:----------:|:----------:|:------:
2|1|1|123|1|100|10|2|0
2|1|2|123|1|150|10|3|0
2|1|1|200|1|100|10|2|0
2|1|2|200|1|150|10|4|0

###Beispiele "Im Freien - Gleiche Ringzahl - Platzierung für das Finalschießen"
*(tiebreaker_1: "10'er+X'er" / tiebreaker_2: "X'er" / tiebreaker_3: "Stechen oder Los")*

Starter "123.1" und "200.1" sind beide die für das Final qualifiziert. 

Starter "123.1" erhält im Losverfahren *(Runde 2 - tiebreaker_3)* einen Punkt und damit den Platz vor Starter "200.1".

event_id|session_id|round_id|participant_id|individual_id|score|tiebreaker_1|tiebreaker_2|tiebreaker_3
:------:|:--------:|:------:|:------------:|:-----------:|:---:|:----------:|:----------:|:------:
2|1|1|123|1|200|10|4|0
2|1|2|123|1|250|10|8|1
2|1|1|200|1|200|10|4|0
2|1|2|200|1|250|10|8|0

###Beispiele "Halle - Gleiche Ringzahl - Einzug ins Finale"
*(tiebreaker_1: "10'er" / tiebreaker_2: "9'er" / tiebreaker_3: "Stechen oder Los")*

Starter "123.1", "200.1" und "093.1" sind ringgleich. Da die Anzahl der "10'er" und "9'er" dabei nicht berücksichtigt wird, hätten alle Drei Anspruch auf den letzten Platz im Finalschießen.

Es wird ein Stechen veranstaltet, bei dem Starter "093.1" das Stechen gewinnt und in (Runde 2 - tiebreaker_3) einen Punkt erhält. Er zieht damit ins Finale. 

Die Plazierungen innerhalb der Qualifikationsrunde bleiben davon unberührt, da in diesem Fall "tiebreaker_3" nicht ausgewertet wird.

event_id|session_id|round_id|participant_id|individual_id|score|tiebreaker_1|tiebreaker_2|tiebreaker_3
:------:|:--------:|:------:|:------------:|:-----------:|:---:|:----------:|:----------:|:------:
2|1|1|123|1|200|10|4|0
2|1|2|123|1|250|12|2|0
2|1|1|200|1|200|12|4|0
2|1|2|200|1|250|13|2|0
2|1|1|093|1|200|10|4|1
2|1|2|093|1|250|11|8|0

###Beispiele "Ein Starter startet mit verschiedenen Bogenarten"
Im ersten Durchgang schießen gleichzeitig Recurve und Compound. Ein Starter (älter als 50 Jahre) hat sich mit für beide Bögen angemeldet und ist mit den Startnummern "123.1" und "123.2" vertreten. 

Im zweiten Durchgang starten er, noch eimal in der Olympischen Klasse Recurve. Er erhält die Nummer "123.3".

event_id|session_id|round_id|participant_id|individual_id|score|tiebreaker_1|tiebreaker_2|tiebreaker_3
:------:|:--------:|:------:|:------------:|:-----------:|:---:|:----------:|:----------:|:------:
2|1|1|123|1|200|10|2|0
2|1|2|123|1|200|10|3|0
2|1|1|123|2|250|10|2|0
2|1|2|123|2|250|10|3|0
2|2|1|123|3|220|10|2|0
2|2|2|123|3|220|10|3|0


[event_id]:kapitel_07.md
[session_id]:kapitel_07.md
[round_id]:kapitel_07.md
[participant_id]:kapitel_07.md
[individual_id]:kapitel_07.md
[score]:kapitel_07.md
[tiebreaker_1]:kapitel_07.md
[tiebreaker_2]:kapitel_07.md
[tiebreaker_3]:kapitel_07.md
