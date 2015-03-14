##Tabelle ”accosiations” 

Diese Tabelle beinhaltet Organisationen (Vereine/Verbände), welche den Teilnehmern zugeordnet werden können. Die Organisation kann eine regionale, nationale aber auch internationale Organisation sein. Ein ”NOC” wäre in diesem Falle eine nationale Organisation.

Sollte es nötig sein darzustellen, dass eine Organisation Mitglied in einer anderen Organisation ist (hierarchische Struktur), kann das Feld ”part_of” genutzt werden. In diesem Feld wird die ”association_id” der übergeordneten Organisation eingetragen. 

Alle Organisationen werden in einer Tabelle gespeichert. Die hierarchische Ordnung ergibt sich aus der internen Verknüpfung der Datensätze über das Feld ”part_of”. Auf Grund dieses Mechanismus ist die maximale Tiefe der hierarchischen Ordnung nicht vorgegeben oder eingeschränkt.

Dem Teilnehmer wird nur der Eintrag mit der kleinsten Hierachiestufe zugewiesen. Alle anderen ergeben sich aus den hinterlegten Verknüpfungen.

Bezogen auf ”NOC” würde ”title” den Namen der Nation enthalten und ”title_short” das Kürzel der Nation.

####Schlüsselfelder

* [event_id]
* [association_id]

####Felder

* [title_short]
* [title]
* [part_of] (Verweis zu einem anderen Eintrag der Tabelle)

###Beispiele

[event_id]|[association_id]|[title_short]|[title]|[part_of]|Bemerkung
:--------:|:--------------:|:------------|:------|:-------:|:---------
1|1|BSC|Bogensportclub|<null>|Event 1 ist eine Kreismeisterschaft bei der unter anderem "BSC" antritt
...|...|...|...|...|
2|1|LV1|Landesverband 1|<null>|Event 2 ist eine Deutsche Meisterschaft bei der die Landesverbände registriert werden
2|2|LV2|Landesverband 2|<null>|ein weiterer Landesverband
2|10|BSC|Bogensportclub|1|"BSC" ist im "Landesverband 1" organisiert 
2|11|TSG|Turn- und Sportgemeinschaft|1|"TSG" ist auch im "Landesverband 1" organisiert 
2|12|BSV|Bogensportverein|2|"BSV" ist im "Landesverband 2" organisiert 
...|...|...|...|...|
3|1|DOSB|Deutscher Olympischer Sportbund|<null>|Event 3 ist ein internationales Turnier.
