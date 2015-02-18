##Tabelle ”countries”

Diese Tabelle beinhaltet Regionen, welche den Teilnehmern zugeordnet werden können. Dies können Städte, Kreise, Länder, Kontinente sein.

Sollte es nötig sein darzustellen, dass eine Region Teil einer anderen Region ist (hierarchische Struktur) dann kann das Feld ”part_of” genutzt werden. In diesem Feld wird die ”country_id” der übergeordneten Region eingetragen. 

Alle Regionen/Länder werden in einer Tabelle gespeichert. Die hierarchische Ordnung ergibt sich aus der internen Verknüpfung der Datensätze über das Feld ”part_of”. Auf Grund dieses Mechanismus ist die maximale Tiefe der hierarchischen Ordnung nicht vorgegeben oder eingeschränkt.

Dem Teilnehmer wird nur der Eintrag mit der kleinsten Hierachiestufe zugewiesen. Alle anderen ergeben sich aus den hinterlegten Verknüpfungen.

**Schlüsselfelder**

* event_id ([sub:event_id])
* country_id ()

**Felder**

* title_short ([sub:title_short])
* title ([sub:title])
* part_of (Verweis zu einem andren Eintrag der Tabelle [sub:Tabelle-”countries”])
