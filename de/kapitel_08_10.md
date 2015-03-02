##Ligawettkampf mit vier Spieltagen

Die Verwaltung einer Liga-Runde kann mit denen in [oasdb] beschiebenen Tabellen wie folgt ungesetzt werden.

**Vorbereitung des gesamten Ablaufes**

* Für den Liga-Wettkampf wird eine [Veranstaltung] mit vier [Durchgängen] angelegt.
* Jeder [Durchgang] ist ein Spieltag. Dem Spieltag werden Daten wie **Austragungsort**, **Datum** zugeordnet.
* Die Mannschaften ([teams]) eingetragen werden, die sich an dem Wettkampf beteiligen.
* Die Starter werden in die Tabelle [Mannschaftsmitglieder] eingetragen, wobei sie gleichzeitig den [Mannschaften] zugeordnet werden.
* Zusätzlich können werden Kampfrichter und Helfer als [Teilnehmer] aufgenommen werden.

**Unmittelbare Vorbereitung vor jedem Spieltag**

* Der Leiter der Liga legt die [Startplätze] für alle Matches an dem Tag fest. Entweder er setzt die Mannschaften per Hand oder er bedient sich vorher festgelegter Regeln, die eine automatische Setzung zulassen.

**Arbeit am Wettkampfort**

* Der Ausrichter übernimmt aus der Tabelle [Startplätze] die Startaufstellung und kann diese als Übersicht für den gesammten Tag und die Match-Ergebnislisten ausdrucken.
* Aus der Tabelle [Mannschaftsmitglieder] kann eine Übersicht für den Kampfrichter erstellt werden, aus der die möglichen Schützen hervorgehen. Der Ausrichter muss Nachmeldungen entgegen nehmen können.
* Für die Schnelleingabe werden Match-Ergebnisse werden als [Mannschaftsergebnisse] aufgenommen.
* Die [Einzelergebnisse] werden zusaätzlich aufgenommen, da aus ihnen der Einatz der Schützen hervorgeht. *Der Kampfrichter sammelt vor jedem Match die Startermeldungen der Mannschaftsführer ein, kontrolliert deren Einhaltung.* 

**Datenübermittlung Ligaleiter <> Ausrichter**

Besteht eine direkte Verbindung zur Datenbank, so können die Ergebnisse direkt vom Ausrichter in das System eingepflegt werden.

An sonsten muss der Ligaleiter eine Austauschdatei an den Ausrichter senden, der diese mit den notwendigen Daten füllt und zurück sendet.

[oasdb]: ../Readme.md
[Veranstaltung]: kapitel_08_10.md
[Durchgang]: kapitel_08_10.md
[Durchgängen]: kapitel_08_10.md
[participants]: xx.md
[Teilnehmer]: xx.md
[teams]: xx.md
[Mannschaften]: xx.md
[Startplätze]: xx.md
[Mannschaftsmitglieder]: xx.md
[Mannschaftsergebnisse]: xx.md
[Einzelergebnisse]: xx.md
