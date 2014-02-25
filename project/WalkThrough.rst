========================================
UI2 FS2014 DropTable Cogitive Walktrough
========================================

:Gruppe: DropTable
:Teilnehmer: Tobias Blaser, Philipp Christen
:Email: tblaser(at)hsr.ch, pchriste(at)hsr.ch



1 Getestetes Produkt
====================

CLX.Stage: Editor für Stage E-Learning System.

Es werden nur Testseiten getestet, keine Infoseiten.


2 Benutzerprofile
=================

2.1 Autor
----------

Autoren erstellen Module und deren Inhalte.


2.2 Anwender (Teilnehmer)
-------------------------

Teilnehmer bearbeiten die Lerninhalte, beantworten dabei auftauchende Fragen und sehen sich die Auswertungen an.

2.3 Weitere
-----------

Neben den Autoren und Teilnehmern gibt es noch Kursleiter, welche für die Ausführung und Auswertung der Lerninhalte zuständig sind. Diese fallen aber nicht in den Rahmen dieser Untersuchung. Zudem kommt es vor, dass Autoren gleichzeitig auch Kursleiter sind, insbesondere in Schulen.
 
3 Aufgaben und Probleme
=======================

.. note:: **Voraussetzung:** CLX.Stage wurde korrekt installiert und gestartet.

3.1 Lerninhalte erstellen
-------------------------

Ausgangspunkt für den Autor ist das geöffnete Programm ohne geladenes Modul.
.. figure:: stepScreens/3.0.Ausgangslage_Autor.png

3.1.1 Modul erstellen
.....................

.. figure:: stepScreens/3.1.1_1.Modulerstellung.png
.. figure:: stepScreens/3.1.1_2.Templateauswahl.png
.. figure:: stepScreens/3.1.1_3.wechsel_zu_testmodulvorlagen.png
.. figure:: stepScreens/3.1.1_4.ordnerauswahl.png
.. figure:: stepScreens/3.1.1_5.neues_modul.png

3.1.1 Seite anlegen
...................
	
	
3.1.2 Kapitel erstellen
.......................


3.1.3 Test erstellen (Editor)
.............................

**Schritte**

Video: http://www.mediafire.com/watch/7br4m5fj37u69s8/screenrecording_clx_stage_UINT2.wmv

1) Neuen Kapitelinhalt anlegen
2) Kategorie auswählen
3) Element auswählen
	
**Inhaltstypen**

1) Multiple Choice
2) Single Choice Matrix
3) Drag-Drop


3.1.20 Single Choice Matrix bearbeiten
.......................................

.. figure:: stepScreens/3.1.20-1.jpg

   3.1.20-1: Element Auswählen


* Sichtbarkeit Aktion
	* **Problem:** Teilnehmer weiss nicht, wie er das Element bearbeiten kann (Doppelklick).
	* **Grund:** Es gibt keinen Button, mit dem das Editieren aufgerufen werden kann. Benutzer muss ausprobieren.


.. figure:: stepScreens/3.1.20-2.jpg

   3.1.20-2: Text bearbeiten


.. figure:: stepScreens/3.1.20-3.jpg

   3.1.20-3: Optionen Eigenschaften aufrufen


* Nächster Schritt
	* **Problem:** Teilnehmer ist nicht klar, was er jetzt machen soll.
	* **Grund:** Es werden viele Elemente angezeigt, die in der aktuellen Ansicht gar keinen Sinn machen.
	


.. figure:: stepScreens/3.1.20-4.jpg

   3.1.20-4: Option Name bearbeiten


.. figure:: stepScreens/3.1.20-5.jpg

   3.1.20-5: Eigenschaftsfenster von Feldern aufrufen


* Sichtbarkeit Aktion
	* **Problem:** Für den Teilnehmer kommt es unerwartet, das die Eigenschaften diesmal über das Menü aufgerufen werden.
	* **Grund:** Im Vergleich zum Bearbeiten der Eigenschaften der andern Elemente wird dieses Eigenschaftsfenster über das Menü gestartet.


.. figure:: stepScreens/3.1.20-6.jpg

   3.1.20-6: Einstellungen Antworten verändern


.. figure:: stepScreens/3.1.20-7.jpg

   3.1.20-7: Musterantwort auswählen


3.2 Quiz durchführen (Teilnehmer)
---------------------------------

3.2.1 Quiz starten
..................

.. figure:: stepScreens/3.2.1-1.png

   3.2.1-1: Start Screen eines E-Learnings



3.2.2 Fragen / Antworten
........................

.. figure:: stepScreens/3.2.2-1.png

   3.2.2-1: Multiple Choice Frage


* Nächster Schritt
	* **Problem:** Teilnehmer ist nicht klar ob er eine Antwort oder mehrere anklicken darf. --> Instruktionen muss er zuerst ausklappen.
	* **Grund:** Der Teilnehmer wird nicht aufgefordert irgend etwas zu tun (z.B. "Bitte wählen Sie eine oder mehrere Antworten an").
* Sichtbarkeit Aktion
	* **Problem:** Teilnehmer weiss nicht, welchen Knopf er nun drücken muss.
	* **Grund:** Zu bevorzugende Aktionbutton (weiter >) ist nicht speziell gekennzeichnet.


.. figure:: stepScreens/3.2.2-2.png

   3.2.2-2: Single Choice Matrix Frage


.. figure:: stepScreens/3.2.2-3.png

   3.2.2-3: Drag'n Drop Frage


3.2.3 Antworten / Auswertung
............................

.. figure:: stepScreens/3.2.3-1.png

   3.2.3-1: Fragen abschliessen und zu Auswertung übergehen


* System Zustand
	* **Problem:** Teilnehmer wird nach Auswertung gefragt, befindet sich aber noch gar nicht beim letzten Schritt (4 von 5).
	* **Grund:** Für den Teilnehmer ist es nicht ersichtlich, das die Auswertungsseite in die "Nummerierung" einberechnet wird. -> Verwirrt, das plötzlich Auswertung kommt.


.. figure:: stepScreens/3.2.3-2.png

   3.2.3-2: Auswertung
   

* System Zustand
	* **Problem:** Teilnehmer ist unklar, ob er den Test als ganzes bestanden hat oder nicht. Zudem ist erst auf den zweiten Blick erkennbar, welche Fragen richtig und welche falsch beantwortet wurden.
	* **Grund:** (Beim Welcome Screen stand 80%), hier wird nur die erreichte Zahl angzeigt (Teiln. muss sich erinnern). Das Gleiche gilt für die Fragen.
	
	
.. figure:: stepScreens/3.2.3-3.png

.. figure:: stepScreens/3.2.3-4.png

   3.2.3-4: Antworten einsehen


* Aktion Sichtbarkeit
	* **Problem:** Teilnehmer sieht keine Möglichkeit, zur Übersicht zurückzukehren.
	* **Grund:** Zurückkehr-Aktion fehlt
* Nächster Schritt
	* **Problem:** Teilnehmer weiss nicht genau, was er jetzt machen muss/soll. Zurückgehen geht nicht. Nächste Frage?
	* **Grund:** Teilnehmer wird zu wenig geführt. -> Muss ausprobieren


.. figure:: stepScreens/3.2.3-5.png

   3.2.3-5: Auswertung ein-/ausblenden


* Aktion Sichtbarkeit
	* **Problem:** Teilnehmer sieht nicht, das das Auge nicht signalisiert, das er sich im Auswertungsmodus befindet sondern sich damit die Auswertung ein-/ausschalten lässt.
	* **Problem:** Funktion ist nicht als solche erkennbar (Button?), Hover-Hilfe ist unverständlich.

