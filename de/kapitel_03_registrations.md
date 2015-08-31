##Tabelle "registrations"

Die Wettkampfteilnehmer sollen sich selbst zu einem Wettkampf anmelden und die eigenen Angaben bis zu einem Stichtag ändern können. 

Die Anmeldung erfolgt in einer separaten Tabelle um die Konsistenz der Tabellen "[participants]" und "[individuals]" nicht zu gefährden.

Die Daten können in die beiden Tabellen übernommen werden. Diese Übernahme wird durch den Verwalter der Veranstaltung ausgeführt. Er kann/muss die Anmeldungsdaten noch einmal korrigieren.

Im Gegensatz zu diesem beiden Tabellen sollten die Inhalte der Tabelle "registrations" *nicht* veröffentlicht werden.

Die möglichen Angaben "[class_id]" und "[division_id]" werden aus der Tabelle "[categories]" entnommen.

Auch die Angaben in "[member_of_country]" und "[member_of_assosiation]" führen direkt zu Einträgen in den entsprechenden Tabellen.

####Schüsselfelder

* [event_id]
* [registration_id]

####Felder

* [first_name]
* [middle_name]
* [last_name]
* [gender]
* [date_of_birth]
* [member_of_country]
* [member_of_assosiation]
* [class_id]
* [division_id]
* [comment]


[categories]:kapitel_02_07.md
[class_id]:kapitel_07_c.md#class_id
[division_id]:kapitel_07_d.md#division_id
[member_of_assosiation]:kapitel_07_a.md#assosiation
[individuals]:kapitel_03_04.md
[comment]:kapitel_07_c.md#comment
[participants]:kapitel_03_03.md
[event_id]:kapitel_07_e.md#event_id
[participant_id]:kapitel_07_p.md#participant_id
[first_name]:kapitel_07_n.md#name
[middle_name]:kapitel_07_n.md#name
[last_name]:kapitel_07_n.md#name
[gender]:kapitel_07_g.md#gender
[date_of_birth]:kapitel_07_d.md#date_of_birth
[member_of_country]:kapitel_07_c.md#country
[countries]:kapitel_03_02.md
[registration_id]:kapitel_07_r.md#registration_id
