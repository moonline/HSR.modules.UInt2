====================
UsabilityTest Report
====================


:Gruppe: DropTable
:Teilnehmer: Tobias Blaser, Philipp Christen
:Email: tblaser(at)hsr.ch, pchriste(at)hsr.ch
:Getestetes Produkt: CLX.Stage Editor für Stage E-Learning System der Firma CREALOGIX AG


1 Testmethodik
==============


.. list-table:: Testteilnehmer
   :widths: 30 30 30
   :header-rows: 1

	* - Eigenschaft
	  - Teilnehmer 1
	  - Teilnehmer 2
	* - Geschlecht
	  -
	  -
	* - Alter
	  -
	  -
	* - Beruf
	  -
	  -


2 Kontext
=========

Der Usability Test besteht aus praxisnahen Beispielen. Die meisten Aufgaben sind eigenständig, ein paar bauen aufeinander auf.


3 Test Aufbau
=============

Der Testuser erhält ein Notebook mit installiertem Browser, Adobe Air und CLX.Stage. Je nach Aufgabe erhält der Benutzer ein bereits vorbereitetes Modul, wie in der jeweiligen Beschreibung erwähnt.


4 Ergebnisse
============

4.1 Validierte Probleme
-----------------------

Aufgabe 1
.........

* Modul->neu erstellen->Vorlagen->Testlayout Deutsch
* Erstellen-Button ausgegraut -> Doppelklick -> möchte Projektordner wissen -> Ohne Drücken von "Erstellen" angelegt
* Neue Seite anlegen: 
	* [Seitenelemente +]
		* überforder Nutzer
		* falsch
	* [+] im linken Bereich
		* Keine Begrüssungsseite gefunden (Einführungsseite)
		* Wählt Begrüssungsseite -> Fenster bleibt offen
		* Kapitel und Chapters verwirren Benutzer
		* Benutzer findet Begrüssungsseite nicht
		* Benutzer löscht andere erstelle Frageseiten
		* Benutzer findet Speicherfunktion nicht -> Nimmt an, das automatisch gespeichert wurde.



4.2 Nicht validierte Probleme
-----------------------------

Aufgabe 2
.........

* File öffnen


Aufgabe 3
.........

* Benutzer wählt erste der Auswahl
* Benutzer schiebt nach unten


Aufgabe 4
.........

1) öffnen
2) neue Frage
3) "Sofort Feedback" ausgewählt
4) hoch schieben
5) Bearbeitet Titel
6) Findet Ort zum Hinzufügen von neuen Auswahlantworten nicht
	1) Sucht im Dialog Seitenelemente
	2) Fügt gefundenes Element hinzu
	3) Falsch -> Benutzt undo (zuerst mit Ctrl-Z, was nicht funktionierte)
	4) Findet richtiges Element nicht
	5) Elemente, die nicht kompatibel sind können ausgewählt werden. Auswahl --> Meldung, dass dieses Element nicht kompatibel ist mit der Vorlage
	6) Icon ist ein T (völlig unlogisch, steht für Text)
7) Richtige Auswahl definieren 
	1) Rechtsklick ist es nicht (Flash)
	2) Buttons unten auch nicht
	3) Checkbox/Radiobutton oder Pinker Rahmen links davon auch nicht
	4) Einstellungen->
		* Sofort Feedback? Nein
		* Findet Auswahl
		* "Aufgabentypen" schlechte Bezeichnung

Aufgabe 5
.........

1) Öffnen
	1) Öffnet start.html in Browser, gibt Fehlermeldung (weil Chrome --> Flash-Sandbox) 
	2) Startet Stage, Modul öffnen --> ist verwirrt, öffnet aber config.xml.
2) Seite einfügen
	1) Plus-Button kein Problem
	2) Aufgabenseiten-Reiter fast nicht sichtbar
	3) Vorlagen-Window verschwindet nicht!
3) Seite öffnen?
	1) Bleistift-Icon --> steht für umbenennen
	2) Rechtsklick --> geht nicht
	3) Probiert Doppelklick --> Erfolg!
4) Text bearbeiten
	1) Markiert Textelement, beginnt zu tippen --> geht nicht
	2) Will Text markieren, verschiebt Element
	3) Bleistift-Icon --> Erfolg.

Aufgabe 6
.........

1) Wählt Vorlage "Drag and Drop (Text)" statt erwarteten "Matrix-Multiple-Choice (mit Sofortfeedback)" aus, weil es keine Matrix-Single-Choice gibt (Problem der Aufgabenstellung?)
	1) Vorlagen-Fenster verschwindet nicht!
	2) Nach Doppelklicken auf die Vorlage wird ein Wizard o.Ä. erwartet
2) Text ändern
	1) Ändert Text auf Target
	2) Versucht, Text auf Drop-Area einzugeben --> geht nicht
	3) versucht, Bleistift-Icon auf Drop-Area anzuwenden --> keine Auswirkungen, verwirrt, probiert es noch einmal.
	4) Öffnet Optionen, findet aber keinen Eintrag.
	5) Kapiert das System mit den Draggables. Doppelklickt auf Text
	6) Text in Texteditor ist weiss, ist verwirrt. Stellt Text auf Schwarz um!
3) Lösung zuweisen
	1) Nimmt richtige Möglichkeit an und zieht Draggables auf Drop-Areas. Meint aber, dass es eine Raten war und nicht Intuition.

Nach Hinweis, dass eigentlich das Problem mit den Checkboxen/Radiobuttons gemeint war, erstellt Teilnehmer ohne Probleme eine neue Seite. Er versucht dann aber, die Seite anzupassen (in den Optionen), ohne dass sie in der Vorschau geöffnet wurde!

Aufgabe 7
.........

Kein Problem, Schwierigkeiten wurden bereits in vorherigen Aufgaben geklärt.

Aufgabe 8
.........

1) Versteht nicht, was ein Seitentitel ist. Trifft aber die richtige Annahme.
2) Text bearbeiten
	1) Doppelklick auf Titelelement, sieht ={pageTitle}
	2) nimmt richtig an, dass es ein Flag ist (stutzt aber)
	3) nimmt richtig an, dass der richtige Parameter irgendwo hinterlegt ist. Bearbeitet aber um die Aufgabe zu lösen den Text direkt.
3) Suche nach dem "richtigen" Parameter
	1) Rechtsklick auf Seite im Modulexplorer --> Nope.
	2) Optionen: Es gibt einen Eintrag bei Gestalt zu Seitentitel, aber nicht bearbeitbar und das Feld ist viel zu klein.
	3) Optionen: Teilnehmer sieht Reiter "Seite" und vermutet, dass der Parameter dort sein könnte.

Aufgabe 9
.........

Teilnehmer sieht kein Problem, erstellt eine Aufgabenseite ohne Auswertungsseite (Zufall)

Aufgabe 10
..........

1) Findet den inhaltlichen Fehler (deutsche Mark) und benennt einfach den Eintrag um. Sieht dann aber die Spalte "Euro" und kommt zum richtigen Schluss
2) Klickt auf "Info", aber es passiert nichts.
3) Sucht in Optionen, gibt aber schnell auf.
4) versuchts, Feedback-Icon bei Deutschland von "deutsche Mark" zu "Euro" zu verschieben. --> Verschiebt ganze Row!
5) Schiebt Row zurück, verrutscht aber, Row ist plötzlich unter einer anderen versteckt, muss diese auch wegschieben. (Alle Rows sind schlussendlich nicht mehr im Flow...)
6) Wieder in den Optionen, dent es sei in der Flow-Liste!
7) findet den richtigen Eintrag. Erwartet, dass beim Aufruf der Optionen mit markiertem Element gerade der richige Reiter aufgerufen wird. (Kontextsensitiv)

Aufgabe 11
..........

Teilnehmer kennt Vorgehen zu "Single"-Matrix-Aufgaben noch aus Aufgabe 6 und hat keine Probleme bei der Aufgabe.

Aufgabe 12
..........

Teilnehmer kennt Vorgehen zum Umbenennen bei Draggables noch aus Aufgabe 8 und hat keine weiteren Probleme.
Der Abspielmodus ist auch kein Problem. Etwas Verwirrtheit bei Auswertungsseite.



4.3 Neu aufgetauchte Probleme
-----------------------------

* Tool merkt sich zuletzt benutzten Pfad nicht beim Öffnen von Modulen
