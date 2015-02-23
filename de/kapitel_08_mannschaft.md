##Mannschaften

Mehrere Teilnehmer können als Mannschaft starten. Jedoch gibt es zwei grundsätzliche Arten von Mannschaften, die auch unterscheidlich behandelt werden müssen.

Aus Sicht der Datenbank ist die Frage zu klären ”Werden die Ergebnisse auf einem Aufschreibezettel der Mannschaft geführt oder hat jeder Starter seinen eigenen Zettel?”.

###Mannschaftsart "Gruppe von Einzelstartern", "Gruppenwertung" oder "Mannschaftswertung"

Jeder Starter führt jeder Starter seine eigenen Aufschreibezettel. Die Einzelergebnisse mehrere Teilnehmer eines Wettkampfes werden als Mannschaftsergebnis zusammengefasst.

* Die Mannschaft besteht in der Regel aus drei Startern. 
* Die Starter können während des Wettkampfes nicht gewechselt werden.

In den Wettkampfaufzeichnungen muss folgendes ersichtlich sein:

* Einzelstarter
  * der Startplatz
  * die Kategorie
  * das Ergebnis
  * die Platzierung

* Mannschaft
  * die Kategorie
  * das Ergebnis (Summe der Einzelstarter)

* die Plazierung

###Mannschaftsart "Mannschaft" oder "Mannschaftswettbewerb" 

Es gibt pro Mannschaft einen Aufschreibezettel. Die Zettel können so angelegt sein, dass die Ergebnisse der einzelnen Starters in extra Spalten oder Zeilen hinterlegt werden. 

* Die Mannschaft besteht in der Regel aus drei Startern. 
* Die Starter können während des Wettkampfes nicht gewechselt werden.
* In Bezug auf die Bogendisziplin sind homogene Mannschaften (z.B. Recurve) aber auch heterogene Mannschaften (z.B. ”Recurve gemischt” oder ”3D Langbogen, Instinktivbogen, Compound) möglich.
* In Bezug auf die Altersklasse sind homogene Mannschaften (z.B. Damen) aber auch heterogene Mannschaften (z.B. ”Gemischt”) möglich. Das Alter tritt oft in den Hintergrund.

In den Wettkampfaufzeichnungen muss folgendes ersichtlich sein:

* Einzelstarter
  * die Kategorie (Es sollte ersichtlich sein, dass die Mannschaften richtig zusammengestellt waren.)
  * das Ergebnis (Es sollte ersichtlich sein wie viele Ringe der Einzelne geschossen hat.)

* Mannschaft
  * der Startplatz
  * die Kategorie
  * das Ergebnis
  * die Plazierung

###Mannschaftsart "Liga-Team"

Liga Team für das mehrere Teilnehmer gemeldet sein können, jedoch nur drei Starter pro Match zugelassen sind. Für die Erfassung der Ergebnisse erhält jede Mannschaft einen Zettel.

Insofern kann ein "Liga-Team" als "Mannschaft" gesehen werden.

* In Bezug auf die Bogendisziplin sind nur homogene Mannschaften (z.B. Recurve) möglich.
* Die Altersklasse wird in der Regel nicht beachtet.
* Die Mannschaft kann aus bis zu 10 Startern bestehen.
* Pro Match starten drei Mitglieder einer Mannschaft. Die Mitglieder können von Match zu Match getauscht werden.

In den Wettkampfaufzeichnungen muss folgendes ersichtlich sein:

* Einzelstarter
  * die Kategorie (Es sollte ersichtlich sein, dass die Mannschaften richtig zusammengestellt waren.)
  * das Ergebnis (Es muss ersichtlich sein wie viele Ringe der Einzelne geschossen hat.)
  
* Mannschaft
  – der Startplatz
  – die Kategorie
  – das Ergebnis
  – die Plazierung

###Zusammenfassung

Im Fall "Gruppenwertung" muss man feststellen, dass die Einzelergebnisse ausschlaggebend sind und die Gruppenwertung sich lediglich aus der Addition dieser Einzelergebnisse ergibt.

Im Fall "Mannschaft" und "Liga-Team" werden die Ergebnisse als Mannschaft erzielt werden. Ergebnisse und Kategorie des Einzelnen werden hinterlegt um nachvollziehen zu können ob das Mannschaftsergebnis korrekt zustande gekommen ist.

Es wird daher im weiteren mit zwei Tabellen gearbeitet, welche Mannschaften beinhalten

* "club_teams" - Gruppe von Einzalstartern
* "teams" - Mannschaften / Liga-Teams
