====================
UsabilityTest Report
====================


:Gruppe: DropTable
:Teilnehmer: Tobias Blaser, Philipp Christen
:Email: tblaser(at)hsr.ch, pchriste(at)hsr.ch
:Getestetes_Produkt: CLX.Stage Editor für Stage E-Learning System der Firma CREALOGIX AG



1 Testmethodik
==============

============  =========  =====  ==========  ============  =======================  =========
Teilnehmer #  Name       Alter  Geschlecht  Beruf         Vorkenntnisse CLX.Stage  Durchgang
============  =========  =====  ==========  ============  =======================  =========
1             Z.Oussama  21     m           Informatiker  keine                    A        
2             N.Grögli   20     m           Informatiker  keine                    A        
3             J.Aeberli  20     m           Informatiker  sehr grosse              B        
============  =========  =====  ==========  ============  =======================  =========



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

Aufgabe 1 in Durchgang A
........................

Protokoll Testablauf
^^^^^^^^^^^^^^^^^^^^

1) Modul -> Neu erstellen -> Vorlagen -> Lernkapitel Deutsch
2) Erstellen-Button ausgegraut -> Doppelklick -> System fragt nach Projektordner -> Projektordner wurde ohne Wissen des Benutzers angelegt (Ohne Drücken von "Erstellen"), verwirrt Benutzer
3) Benutzer will neue Seite anlegen, sucht nach Button/Command: 
	1) [+] im rechten Bereich (Seitenelemente)
		* öffnender Dialog überforder Nutzer
		* war falscher Ansatz
	2) [+] im linken Bereich
		1) Keine Begrüssungsseite gefunden (Einführungsseite)
		2) Wählt Begrüssungsseite -> Fenster bleibt offen (verwirrt Benutzer)
		3) Kapitel und Chapters verwirren Benutzer
		4) Benutzer findet Begrüssungsseite nicht
		5) Benutzer wählt Einführungsseite
		6) Benutzer löscht andere erstelle Frageseiten
		7) Benutzer findet Speicherfunktion nicht -> Nimmt an, das automatisch gespeichert wurde.


Aufgabe 3 in Durchgang A
.....................

Protokoll Testablauf
^^^^^^^^^^^^^^^^^^^^

1) Benutzer öffnet Dialog für neue Elemente
2) Benutzer sucht nach Multiple-Choice Seite
3) Benutzer findet mehrere, die ähnlich klingen -> wählt erste der Auswahl (Glückstreffer)
4) Benutzer schiebt an falscher Position eingefügte Seite nach unten


Aufgabe 4 in Durchgang A und B
...........................

Protokoll Testablauf Durchgang A
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1) Benutzer wählt Öffnen
2) Erstellt neue Frage
3) "Sofort Feedback" ausgewählt
4) Schiebt eingefügte Seite hoch da sie an falscher Position eingefügt wurde
5) Benutzer Bearbeitet Titel
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
		* Benutzer findet Auswahl
		* "Aufgabentypen" -> schlechte Bezeichnung


Protokoll Testablauf Durchgang B
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1) Öffnet das Lernmodul
2) Erstellt neue Frage mit der Vorlage "Multiple Choice (mit Auswerten-Button)"
3) Ändert die Texte der Optionen
	1) Stage stürzt ab.
	2) Teilnehmer öffnet Modul neu -> Weiterhin fehlerhaftes Verhalten
	3) Teilnehmer startet die Applikation neu --> Fehler behoben. Ursacher aber unklar.
4) Fügt eine weitere Option hinzu
	1) Sucht in den Optionen, findet den richtigen Ort aber nicht
	2) Wählt schliessliche den Plus-Button um neue Elemente hinzuzufügen --> korrekt
5) Lösungen definieren ist kein Problem


Aufgabe 5 in Durchgang A
.....................

Protokoll Testablauf
^^^^^^^^^^^^^^^^^^^^

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


Aufgabe 6 in Durchgang A
.....................

Protokoll Testablauf
^^^^^^^^^^^^^^^^^^^^

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

Aufgabe 8 in Durchgang A
.....................

Protokoll Testablauf
^^^^^^^^^^^^^^^^^^^^

1) Versteht nicht, was ein Seitentitel ist. Trifft aber die richtige Annahme.
2) Text bearbeiten
	1) Doppelklick auf Titelelement, sieht ={pageTitle}
	2) nimmt richtig an, dass es ein Flag ist (stutzt aber)
	3) nimmt richtig an, dass der richtige Parameter irgendwo hinterlegt ist. Bearbeitet aber um die Aufgabe zu lösen den Text direkt.
3) Suche nach dem "richtigen" Parameter
	1) Rechtsklick auf Seite im Modulexplorer --> Nope.
	2) Optionen: Es gibt einen Eintrag bei Gestalt zu Seitentitel, aber nicht bearbeitbar und das Feld ist viel zu klein.
	3) Optionen: Teilnehmer sieht Reiter "Seite" und vermutet, dass der Parameter dort sein könnte.


Aufgabe 10 in Durchgang A
......................

Protokoll Testablauf
^^^^^^^^^^^^^^^^^^^^

1) Findet den inhaltlichen Fehler (deutsche Mark) und benennt einfach den Eintrag um. Sieht dann aber die Spalte "Euro" und kommt zum richtigen Schluss
2) Klickt auf "Info", aber es passiert nichts.
3) Sucht in Optionen, gibt aber schnell auf.
4) versuchts, Feedback-Icon bei Deutschland von "deutsche Mark" zu "Euro" zu verschieben. --> Verschiebt ganze Row!
5) Schiebt Row zurück, verrutscht aber, Row ist plötzlich unter einer anderen versteckt, muss diese auch wegschieben. (Alle Rows sind schlussendlich nicht mehr im Flow...)
6) Wieder in den Optionen, dent es sei in der Flow-Liste!
7) findet den richtigen Eintrag. Erwartet, dass beim Aufruf der Optionen mit markiertem Element gerade der richige Reiter aufgerufen wird. (Kontextsensitiv)



4.2 Nicht validierte Probleme
-----------------------------

Aufgabe 1 in Durchgang B
........................

Aufgabe 2 in Durchgang A und B
..............................

Stellt für den Teilnehmer 1 kein Problem dar, da er die richtige Vorlage ausgewählt hat.

Aufgabe 7 in Durchgang A und B
..............................

Teilnehmer hatten kein Probleme, Schwierigkeiten wurden bereits in vorherigen Aufgaben geklärt.

Aufgabe 9 in Durchgang A und B
..............................

Teilnehmer sahen keine Probleme, erstellten eine Aufgabenseite ohne Auswertungsseite.

Aufgabe 11 in Durchgang A und B
..............................

Teilnehmer 2 kennt Vorgehen zu "Single"-Matrix-Aufgaben noch aus Aufgabe 6 und hat keine Probleme bei der Aufgabe.

Aufgabe 12 in Durchgang A und B
..............................

Teilnehmer kennt Vorgehen zum Umbenennen bei Draggables noch aus Aufgabe 8 und hat keine weiteren Probleme.
Der Abspielmodus ist auch kein Problem.

4.3 Neu aufgetauchte Probleme
-----------------------------

* Tool merkt sich zuletzt benutzten Pfad nicht beim Öffnen von Modulen
* Neue Seite wird an falscher Position eingefügt, da der Benutzer nicht explizit den Einfügepunkt wählen muss
* Kapitel-/Seitenvorlagen: Zweiter Reiter (Aufgabenseiten) ist zu weit unten im Akkordeon; Teilnehmer bemerken den Reiter fast nicht
* Teilnehmer wollen Änderungen manuell speichern (drücken Ctrl-S oder erwarten Option unter Modul/Speichern o.Ä.)
