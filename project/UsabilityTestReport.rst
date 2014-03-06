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

1) Wählt Vorlage Drag and Drop (Text) aus, weil es keine Matrix-Single-Choice gibt (Problem der Aufgabenstellung?)
	1) Vorlagen-Fenster verschwindet nicht!
	2) Nach Doppelklicken auf die Vorlage wird ein Wizard o.Ä. erwartet

Aufgabe 7
.........

Aufgabe 8
.........

Aufgabe 9
.........

Aufgabe 10
.........

Aufgabe 11
.........

Aufgabe 12
.........



4.3 Neu aufgetauchte Probleme
-----------------------------

* Tool merkt sich zuletzt benutzten Pfad nicht beim Öffnen von Modulen
