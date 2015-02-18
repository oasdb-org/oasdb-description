##Tabelle „teammembers“

Diese Tabelle kommt zum Einsatz wenn Wettbewerbe durchgeführt werden, bei denen das Mannschaftsergebnis im Vordergrund steht.

Ausgehend von den Tabellen „participants“ und „teams“ werden die Mannschaften zusammengestellt, und klassifiziert. Die Datenbank lässt es zu, dass ein Teilnehmer („participant“) in zwei Mannschaften startet. Dies muss durch eine Anwendung kontrolliert werden. 

**Schüsselfelder**

* event_id (Fremdschlüssel [sub:Tabelle-”events”])
* session_id (Fremdschlüssel [sub:Tabelle-”sessions”])
* team_id (Fremdschlüssel [sub:Tabelle-”teams”]) 
* participant_id (Fremdschlüssel [sub:Tabelle-”participants”]) 

**Felder**
