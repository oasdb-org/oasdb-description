##Tabelle ”sessions_timetable”

Diese Tabelle beinhaltet den Zeitplan je Durchgang. 

Bei kleinen Wettkämpfen wird man sicher mit zwei Einträgen ”Training” und ”Wettkampf” auskommen. 

####Schlüsselfelder

* [event_id]
* [session_id]
* [session_part]

####Felder

* [label]

###Zum Beispiel

event_id|session_id|session_part|label
:------:|:--------:|:-------------:|:----
1|1|2015-01-01 08:00:00|Training Erster Durchgang
1|1|2015-01-01 08:45:00|Wettkampf - 1. Entfernung 
1|1|2015-01-01 10:30:00|Wettkampf - 2. Entfernung 
1|1|2015-01-01 13:00:00|Siegerehrung 
1|2|2015-01-01 13:30:00|Training Zweiter Durchgang
1|2|2015-01-01 14:15:00|Wettkampf - 1. Entfernung 
1|2|2015-01-01 15:30:00|Wettkampf - 2. Entfernung 
1|2|2015-01-01 17:00:00|Siegerehrung 

[event_id]:kapitel_07_e.md#event_id
[session_id]:kapitel_07_s.md#session_id
[session_part]:kapitel_07_s.md#session_part
[label]:kapitel_07_l.md#label
