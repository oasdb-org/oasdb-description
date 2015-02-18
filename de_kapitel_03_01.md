##Tabelle ”accosiations” 

Diese Tabelle beinhaltet Organisationen (Vereine/Verbände), welche den Teilnehmern zugeordnet werden können. Die Organisation kann eine regionale, nationale aber auch internationale Organisation sein. Ein ”NOC” wäre in diesem Falle eine nationale Organisation.

Sollte es nötig sein darzustellen, dass eine Organisation Mitglied in einer anderen Organisation ist (hierarchische Struktur), kann das Feld ”part_of” genutzt werden. In diesem Feld wird die ”association_id” der übergeordneten Organisation eingetragen. 

Alle Organisationen werden in einer Tabelle gespeichert. Die hierarchische Ordnung ergibt sich aus der internen Verknüpfung der Datensätze über das Feld ”part_of”. Auf Grund dieses Mechanismus ist die maximale Tiefe der hierarchischen Ordnung nicht vorgegeben oder eingeschränkt.

Dem Teilnehmer wird nur der Eintrag mit der kleinsten Hierachiestufe zugewiesen. Alle anderen ergeben sich aus den hinterlegten Verknüpfungen.

Bezogen auf ”NOC” würde ”title” den Namen der Nation enthalten und ”title_short” das Kürzel der Nation.

**Schlüsselfelder**

* event_id ([sub:event_id])
* association_id ()

**Felder**

* title_short ([sub:title_short])
* title ([sub:title])
* part_of (Verweis zu einem andren Eintrag der Tabelle [sub:Tabelle-”accosiations”])
