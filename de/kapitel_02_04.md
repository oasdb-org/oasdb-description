##Tabelle ”sessions_timetable”

Diese Tabelle beinhaltet den Zeitplan je Durchgang. 

Bei kleinen Wettkämpfen wird man sicher mit zwei Einträgen ”Training” und ”Wettkampf” auskommen. 

####Schlüsselfelder

* [event_id]
* [session_id]
* [session_part_id]

####Felder

* [title]

###Zum Beispiel

event_id|session_id|session_part_id|title
:------:|:--------:|:-------------:|:---:
1|1|1|08:00 Training
1|1|2|08:45 Wettkampf - 1. Entfernung 
1|1|3|10:00 Pause 
1|1|4|10:30 Wettkampf - 2. Entfernung 
1|1|5|13:00 Siegerehrung 
1|2|1|13:30 Training
1|2|2|14:15 Wettkampf - 1. Entfernung 
1|2|3|15:00 Pause 
1|2|4|15:30 Wettkampf - 2. Entfernung 
1|2|5|17:00 Siegerehrung 

[event_id]:kapitel_07_e.md#event_id
[session_id]:kapitel_07_s.md#session_id
[session_part_id]:kapitel_07_s.md#session_part_id
[title]:kapitel_07_t.md#title
