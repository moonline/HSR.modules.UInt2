=====================
Usability Test Report 
=====================


:Gruppe: DropTable
:Teilnehmer: Tobias Blaser, Philipp Christen
:Email: tblaser(at)hsr.ch, pchriste(at)hsr.ch
:Produkt: CLX.Stage Editor für Stage E-Learning System
:Hersteller: CREALOGIX AG


Das Redesign wurde in drei Iterationen aufgeteilt. Für jede Iteration wurden zwei Usability Test Durchläufe durchgeführt.

Validierte Probleme
===================




Nicht validierte Probleme
=========================

Iteration 1
-----------

Die Probleme der Aufgaben 1 konnten nicht validiert werden. Die Tester konnten die gestellte Aufgabe erfüllen, ohne mit dem angenommenem Usability Problem anzustehen oder zu scheitern.

* Aufgabe 1
	* P01: Dem Autor ist nicht klar, was er jetzt machen soll. (STONE 1)
		* **Grund:** Es wird kein Hilfetext angezeigt oder gar eine prominente Schaltfläche.
	* P02: Es ist nicht klar, warum jetzt bereits ein Ordner ausgewählt werden muss, obwohl noch kein Content erstellt wurde (STONE 4)
	* P03: Es werden potenziell unerwünschte Seiten (mit Inhalt) erstellt und der Autor wurde nicht darauf hingewiesen. (STONE 3)


Iteration 2
-----------
Die Probleme der Aufgaben 3,4,5,6,8 und 10 konnten nicht validiert werden. Die Tester konnten die gestellte Aufgabe erfüllen, ohne mit den angenommenen Usability Problemen anzustehen oder zu scheitern. Es sind jedoch auch neue Probleme aufgetaucht. Siehe "Neu aufgetauchte Probleme".

* Aufgabe 3
	* P05: (Seite anlegen) Es ist nicht ganz klar, welcher Button die gewünschte Funktion auslöst. (STONE 1)
		* **Grund:** Es gibt zwei identische Buttons für das Hinzufügen (einer für Seiten/Kapitel, einer für Elemente).
	* P06: Autor muss Aufgabenseiten explizit auswählen, obwohl er sich in einem Testkapitel befindet. (STONE 4)
* Aufgabe 4
	* P07: (Eine bestimmte Vorlage suchen) Autor wird leicht verwirrt.
		* **Grund:** Es gibt viele Vorlagen, welche teilweise sehr ähnliche Namen haben. (STONE 5) Was ist der Unterschied zwischen "Multiple Choice (mit Auswerten-Button)" und "Multiple Choice (mit Sofort-Feedback)" resp. welche Vorlage brauche ich?
* Aufgabe 5
	* P08: (Einfügen einer Vorlage in das Modul) Autor weiss nicht, wie er die gewählte Vorlage einfügen soll. (STONE 2)
		* **Grund:** Es existiert keine Schaltfläche.
* Aufgabe 6
	* P09: Autor kann keine Seite vom Typ "Matrix Single Choice" wählen. (STONE 4)
		* **Grund:** Diese existiert nicht, weil die Unterscheidung Multiple/Single erst später auftaucht.
* Aufgabe 8
	* P11: Es ist nicht klar, dass "Dateititel" gleichzeitig der Seitentitel ist. (STONE 1)
* Aufgabe 10
	* P14: Autor könnte versuchen, die Option über die Checkbox des Elements selbst als Lösung zu kennzeichnen (STONE 4)
	* P15: Es ist unklar, warum die anderen Aufgabentypen überhaupt sichtbar sind  (STONE 4)


Iteration 3
-----------

* Aufgabe 13


Neu aufgetauchte Probleme
=========================

Iteration 1
-----------

i) Dialog "Neue Seite / Kapitel": Das Icon (Quadrat mit Häckchen) für Frageseiten verwirrt die Benutzer. Sie sind unsicher was es zu bedeuten hat.
	* Das Icon wurde für die Iteration 2 angepasst (Seite mit Häckchen)

Iteration 2
-----------

i) Dialog "Neue Seite / Kapitel": Das Icon ist noch immer unklar für Benutzer
	a) Das Icon wurde angepasst nach dem ersten Durchlauf (Seite mit Fragezeichen)
	b) Das Icon wurde vom Benutzer im zweiten Durchlauf als Hilfe interpretiert
	c) Daraufhin wurde es zu einer gewöhnlichen Seite geändert
ii) Auswerte Button inkonsistente Benennung: Im Property Inspector steht "Auswerten-Button", im "Neue Seite / Kapitel" Dialog nur "Button".
iii) Auswertung inkonsistente Benennung: "Feedback" und "Auswertung" werden gemischt verwendet.
iv) Speichern Button wird vom Benutzer unten gesucht, da die Applikation wie eine Webapplikation wirkt.
v) Dialog "Neue Seite / Kapitel": Benutzer ist nicht klar, was Multiple- Singlechoice und Matrix ist.
	* Mögliche Massnahme: Statt der Beschreibung unterhalb des Auswahlfeldes anzuzegen wäre ein Help-Overlay mit einem Beispielbild hilfreich
vi) Pfeil im Seitenbrowser wird interpretiert als "Da ist noch mehr Text"
	* Mögliche Massnahme: Pfeil entfernen
	
	
Iteration 3
-----------

i) Benutzer weiss am Ende des Test's nicht, was er jetzt machen soll (Weiter ist disabled). 
   Lösungsvorschlag: Text anzeigen "Der Test ist beendet."
ii) Korrigieren Modus: Benutzer kann richtige Lösungen nicht einsehen. 
    Lösungsvorschlag: Bei falschen Antworten die richtige mit einem blauen Pfeil kennzeichnen.


Inputs
======

Iteration 2
-----------

i) Multiple Choice Frageseite: Bei nur einer Spalte macht "löschen" keinen Sinn.


Iteration 3
-----------

i) "Seite x/y" anstatt Pause-Button im Play Mode
