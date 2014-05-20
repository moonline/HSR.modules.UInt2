========================
UInt2 Miniprojekt Report
========================

.. * Wie weit sind wir?
.. * Was haben wir angeschaut in der ganzen App (Ausblick)
.. * Verbesserungen
.. * Wichtigste Ergebnisse / Erkenntnisse
.. * Wichtigste Fehler (bestätigt / nicht bestätigt / neue)
.. * Lessions learned
.. * Müsste man das redesign noch mal machen nachdem was wir gelernt haben bei den Tests der Redesigns?
.. * Was hat sich bewährt während dem Prototyping?
.. * Foto Projektaufbau & Screenshots

Einleitung
==========
CLX.Stage ist ein Autorentool der Firma Crealogix AG. Es ist ein WYSIWYG-Editor für Lernmodule und Tests im E-Learning-Bereich. Programmiert auf Basis von Adobe.AIR und in Actionscript.
Es bietet die Möglichkeit, in einem grafischen Editor Aufgaben- und Infoseiten zu erstellen und diese danach in einem integrierten Player oder einem externen HTML-Player (auch auf Mobile Devices) abzuspielen.
Über ein Tracking-System auf einem Server können Lernfortschritte verfolgt und ausgewertet werden.
CLX.Stage unterstützt neben den traditionellen Seitentypen wie Multiple Choice oder Text-Inputs auch modernere Methoden wie Drag and Drop oder Cloze-Tests.
Zusätzlich ist es möglich, Medien wie Audio- oder Film-Dateien einzubinden und abzuspielen sowie einfache, zeitgesteuerte Animationen zu erstellen.

.. was ist CLX.Stage und was ist ziel des projekts

Projektstand
============

Im Rahmen des Projektes wurden drei Redesigns für CLX.Stage durchgeführt.
Dabei wurden Teile der Hauptbereiche von CLX.Stage überarbeitet:

* Modul- und Seitenverwaltung
* Editor für Inhalte und Fragen
* Play-Modus

Die durchgeführten Redesigns decken einige wichtige Teile von CLX.Stage ab. 
Bereiche wie z.B. das Management von Vorlagen, das Hinzufügen zusätzlicher Elemente oder komplexere Seiten wie Drag'n'Drop wurden nicht überarbeitet, da das Primärziel des Redesigns die Verbesserung der User Experience für den Endanwender war und der Umfang dem Zeitplan entsprechen musste.

.. figure:: stepScreens/3.1.3_5.alle_texte_geaendert.png

   Ausgangslage: Die Hauptansicht der bestehenden CLX.Stage Applikation
   

.. figure:: redesignedScreens/mainView.ExampleContent.Capitols.png

   Beispielscreen des Redesign
   

Vorgehen & Verbesserungen
=========================

Planung
-------

⇨ `Wochenplanung <Wochenplan.rst>`_

.. .. include:: Wochenplan.rst


Ausgangsapplikation
-------------------

Ausgangspunkt für die Verbesserungen war die bestehende CLX.Stage Applikation. 
Als erstes wurde diese analysiert und mittels "Cognitive Walkthrough" Stück für Stück die Usability
untersucht.

⇨ `Cognitive Walkthrough <WalkThrough.rst>`_

⇨ `Probleme und Tasks <ProblemeTasks.rst>`_

⇨ `Screens und Steps der Applikation <stepScreens/>`_

Anhand der Resultate des "Cognitive Walkthrough" wurden Aufgaben für einen Usability Test
definiert, um die gefundenen Probleme zu bestätigen.

⇨ `Usabilitytest Aufgaben <UsabilityTest.rst>`_

⇨ `Usabilitytesttog Ausgangsapplikation <UsabilityTestLog.rst>`_

Aus dem Testlog und den Problemen & Tasks wurden die Probleme extrahiert, die beim Usabilitytest
verifiziert werden konnten.

⇨ `Usabilitytestreport Ausgangsapplikation <UsabilityTestReport.rst>`_


Redesign
--------

Die gewonnen Erkenntnisse des Usability Tests und die Probleme & Tasks dienten als Ausgangslage
für ein Iteratives Redesign.

⇨ `Redesign CLX.Stage <redesignedScreens/>`_

Die erstellten Screens wurden jeweils für erneute Usabilitytests benutzt.

⇨ `Usabilitytestlog Redesign <UsabilityTestRedesignLog.rst>`_

⇨ `Usabilitytestreport Redesign <UsabilityTestReportRedesign.rst>`_


Entwickelt wurde in Iterationen, um Erkenntnisse aus den ersten Redesigns und Usability-Tests 
in spätere einfliessen lassen zu können. 

1) Modul / Seiten erstellen
2) Inhalte Erstellen
3) Play-Modus


Dabei folgten wir jeweils dem gleichen Schema: 

1) Definieren des Userziels für den jeweiligen Bereich
2) Entwerfen/Diskutieren eines passenden Workflows
3) Umsetzen als Mockups
4) Testen im Rahmen des Usability-Tests.

Dieses Vorgehen hat sich für alle Redesigns bewährt.

.. _Arbeitsplatz:

.. figure:: img/Versuchsaufbau.png

   Versuchsaufbau beim Testing.


Modul / Seiten erstellen
------------------------

Die komplexen und für den Benutzer teilweise unverständlichen Vorgänge zum Erstellen eines neuen 
Modules konnten durch einen verbesserten Prozess ersetzt werden, welcher den Benutzer führt, ihm jedoch auch die Möglichkeiten offen lässt, den Vorgang abzukürzen.
Eine grosse Schwachstelle im alten Design war, dass man sich nach dem Start des Programms auf einem leeren Schirm wiederfand und keine klaren nächsten Schritte vor Augen hatte.

.. figure:: stepScreens/3.1.3_5.alle_texte_geaendert.png

   Das bestehende CLX.Stage überfällt den Benutzer nach dem Start mit Optionen und Möglichkeiten,
   die er zu dem Zeitpunkt noch gar nicht benutzen kann/will. Die für den Benutzer relevanten
   Aktionen (Neue Seite/Kapitel erstellen) verschwinden komplett in der Oberfläche.


.. figure:: redesignedScreens/Screen.Start_cropped.png

   Der neue Startscreen mit Schnellzugriff auf zuletzt geöffnete Module und der Möglichkeit, 
   schnell neue Module zu erstellen. Dem Benutzer werden nur genau die Optionen angezeigt, 
   die in der aktuellen Situation Sinn ergeben. Der Benutzer muss nicht mehr nach den Oprationen suchen,
   sondern wir geführt. Trotzdem besteht die möglichkeit für Poweruser abzukürzen.

   
Weiterhin konnte der Benutzer bisher in bestimmten Abläufen Elemente auswählen, 
welche im aktiven Kontext keinen Sinn ergaben (wiederspricht STONE 1). 
Dies führte im besten Fall zu Fehlermeldungen, wurde aber teilweise dem User nicht gemeldet.
Neu werden dem Benutzer nur noch Elemente angezeigt, die er auch wirklich benutzen kann.

Ebenfalls werden dem Benutzer nur noch die Controls und Informationen angezeigt, die er benötigt.
So zeigte CLX.Stage dem Benutzer nach dem Start einige Controls 
(z.B. den Button für den Property Inspector) der Applikation, obwohl noch keine Seiten angelegt 
oder geladen wurd und entsprechend die Controls für Inhalte nicht benutzt werden können.

Das Erstellen von Kapiteln und Seiten wurde in einem Assistenten zusammengefasst.
Der Benutzer muss nicht mehr technische Unterscheidungen treffen, die ihn möglicherweise verwirren, 
sondern wählt im Assistent aus, was er benötigt. In der betehenden Applikation musste der Benutzer
z.B. die Unterscheidung zwischen Multiplechoice und Multiplechoice Matrix treffen bei der 
Auswahl des Templates.

Zusätzlich wird hier dem Benutzer neu die 
Möglichkeit angeboten, verschiedene Beispielinhalte in die Seiten einzufügen oder nicht. 
Bisher wurde immer ein Beispielinhalt erstellt, was für erfahrene Benutzer eine verschlechterung 
der Effizienz darstellts, da jedes Mal der Inhalt gelöscht werden musste (wiederspricht STONE 3). 

Die Auswahl wird gespeichert, 
so dass ein Anfänger zu Beginn einen Beispielinhalt erhält, so dass er ein Gefühl für den 
Aufbau einer Seite erhält, später kann er diese Einstellung jedoch einfach deaktivieren und das 
Löschen umgehen.

.. figure:: redesignedScreens/Dialog.NewPageContent_cropped.png

   Redesign "Neue Seite erstellen" mittels Assistent. Der Benutzer wählt auf der Linken Seite
   die Vorlage, auf der rechten Seite kann er diese konfigurieren. Dadurch werden ihm im 
   Vergleich zur bestehenden Applikation viel weniger verschiedene Vorlagen angezeigt, was
   die Übersichtlichkeit verbessert.


Inhalte Erstellen
-----------------

Einstellungen für die Seite und Eigenschaften von Inhaltselementen waren bei CLX.Stage 
an verschiedenen Orten untergebracht: Eigenschaften von Inhaltselementen in einer Toolbar 
oberhalb der Seite und Seiteneigenschaften sowie Einstellungen zu den Fragetypen in einer Sidebar. 
Der Benutzer musste genau wissen, was er wo findet. Die zeigte sich in den Usabilitytests durch
lange Suchzeiten der Benutzer.

Neu befinden sich alle Eigenschaften in der 
Sidebar und werden abhängig vom ausgewählten Element und dem aktiven Kontext angezeigt. 
Im Gegensatz zu vorher werden die Controls für Textformatierung nur angezeigt, 
wenn der Benutzer ein Bild markiert hat (wiederspricht STONE 1).

.. figure:: redesignedScreens/PropertyInspector_comparison.png

   Altes und neues Design Property Inspector: Eigenschaften werden dem Benutzer im neuen Design
   kontextabhängig dargestellt. Der Benutzer sieht nur die Eigenschaften, die für das aktuelle
   Element sinnvoll sind (STONE 1).
   

Die Suche durchsucht die Bezeichnungen der verschiedenen Eigenschaften 
und zeigt passende Elemente an. Wird etwa nach "Unterstreichen" gesucht, wird 
automatisch der Bereich "Textformatierung" angezeigt und der Button zum Unterstreichen von 
Text hervorgehoben. Diese Suche wurde in den Usabilitytests nicht getestet, da die Aufbereitung
der Screens sehr aufwändig gewesen wäre.

.. figure:: redesignedScreens/PropertyInspector_searchFunction.png

   Suchfunktion im Property Inspector.
   

Das Erstellen und Bearbeiten von Fragen war für Benutzer ziemlich unverständlich, 
da die Editoren oft Elemente anzeigten, die der Benutzer gar nicht brauchte. 
So wurden dem Benutzer Einstellungsmöglichkeiten zur Aufgabe/Feedback als ganzes angezeigt, 
obwohl er eine einzelne Antwort selektiert hatte.

Auch hier war oft nicht klar, wo eine bestimmte Aktion zu finden ist. 
Neu können einfache Operationen wie das Hinzufügen von Antworten inline im Element 
durchgeführt werden, alle Einstellungen befinden sich in der Sidebar.

.. figure:: redesignedScreens/mainView.Player.Textpage_comparison.png

   Setzen von richtigen Antworten vor und nach dem Redesign. Die Antworten können direkt
   an der Stelle eingestellt werden, wo der Benutzer im Abspielmodus auch die Frage ausfüllt (STONE 4).

   
Usability-Test Resultate
========================

Die Resultate der Usability Tests zeigten, dass das neue UI die Probleme des alten UIs behob.
Keiner der Tester scheiterte in seinem Auftrag. Alle konnten die ihnen gestellten Ziele erreichen.

.. figure:: img/UsabilityTestVideoFrame1.jpg

   Usability-Test am Paper-Prototyp

Während den Tests sind auch einige verbesserungswürdige Punkte am Redesign aufgetaucht. 
So enthielt das neu entwickelte UI einige Icons, welche die Benutzer verwirrten 
(Box mit Checkmark wurde als interaktive Checkbox anstatt als Symbol für eine Aufgabe interpretiert).

Auch über den Systemstatus waren sich die Benutzer nicht immer im klaren. 
Dies ist auf die Unterschiede des Papier-Prototyp gegenüber einem richtigen UI 
zurückzuführen, da der Papier-Prototyp komplexe Zustände wie Selektion, 
Hover oder die Unterscheidung Icons/Buttons/Formularelemente nicht immer verwechslungsfrei wiedergab.

Auf das Redesign zurückzuführende Probleme wurden für den finalen UI-Entwurf noch korrigiert.

⇨ `Usabilitytestreport Redesign <UsabilityTestReportRedesign.rst>`_, Abschnitt "Neu aufgetauchte Probleme".



Tools & Support
===============

Balsamiq Mockup
---------------

Als Mockup-Tool wurde "Balsamiq Mockups" verwendet.
Drafts für User Interfaces lassen sich schnell und einfach zusammenklicken und es bietet viele 
vorgefertigte Elemente mit Möglichkeit, Icons aus einer kleinen aber gut ausgewählten Bibliothek 
auszuwählen. Teilweise stösst man aber schnell an die Grenzen des Tools und muss entweder aus 
anderen Objekten das gewünschte Element zusammensetzen oder es in einem Bildeditor erstellen 
und dann als Image in Balsamiq importieren. So existierte z.B. kein passendes Icon für den
Vorlagetyp "Frageseite". Das von uns verwendete Icon "Kästchen mit Hacken" verwirrte die Benutzer,
da sie davon ausgiengen, das der Hacken bedeutet, das Element wäre ausgewählt.
Aus diesem Grund haben wir das Icon auf dem Paper Prototype für den zweiten Durchlauf
von Hand angepasst.

Als Prototyping Tool ist Balsamiq eher ungeeignet. Es lassen sich zwar Links zwischen einzelnen 
Mockups setzen, 
so dass ein Navigieren zwischen Mockups möglich ist, allerdings lassen sich interaktive Elemente 
wie Menüs oder Formularelemente nicht bedienen.
Somit wäre es erforderlich, dass für jeden Zustand von interaktiven Elementen das Mockup kopiert 
und angespasst würde, was bereits bei Änderungen am Layout sehr umfassende Anpassungen an vielen 
Mockups erfordert. Aus diesem Grund haben wir die Screens ausgedruckt und das Prototyping auf
Papier und nicht am Rechner durchgeführt.

Will man das Mockup auch für Prototyping verwenden, so ist man je nach Projekt mit einem HTML-Mockup oder einem anderen Tool besser bedient als Balsamiq.

.. figure:: img/BalsamiqAtWork.png

   Balsamiq Mockups im Einsatz

Paper Prototyping vs. Tool Prototyping
--------------------------------------

Nach unseren Erfahrungen eignet sich Paper Prototyping nur noch bedingt zum Testen von Prototypen, 
da Paper Prototyping die heute üblichen interaktiven Elemente nicht repräsentativ wiedergeben kann.
Insbesondere Scroll-Elemente, Hover- und Active-Zustände, Markierungen, 
Animationen und interaktive Statussymbole können durch Paper Prototypes gar nicht oder nur mit 
sehr grossem Aufwand ansatzweise abgedeckt werden.
Aus diesem Grund haben wir im Mockup wo möglich auf diese Elemente verzichtet um realistisch 
testen zu können.

Auch das Durchführen der Usabilitytests ist eher umständlich, da mit den vielen Screens, 
aufgeklebten und übereinandergelegten Bereichen und Eingabefeldern sowie dem Übertragen von 
ausgefüllten Feldern auf andere Screens schnell ein unübersichtlicher Arbeitsplatz entstand.

⇨ Illustration Arbeitsplatz_ siehe Abschnitt Vorgehen.


Erkenntnisse ("Lessons Learned")
================================

* Balsamiq Mockup eignet sich zwar gut für Mockups, nicht jedoch für Prototyping Tests
* Wird ein neuer Workflow anhand des Benutzerziele und nicht so dass es irgendwie in eine bestehende Lösung passt entworfen, so ist der Workflow mit grosser Wahrscheinlichkeit einfacher und verständlicher
* Paper Prototyping eignet sich für moderne Applikationen nicht mehr, da es grosse Differenzen zum
  Verhalten und der User Experience der realen Applikation gibt. 
  Siehe Abschnitt "Paper Prototyping vs. Tool Prototyping".
* Paper Prototyping ist sehr aufwendig und zeitintensiv
* Aufbau des Usability Tests, insbesondere der Videoaufnahme ausserhalb eines Usability-Labors ist
  eine komplizierte Angelegenheit und erfordert Improvisation, da z.B. eine Halterung fehlt um
  die Kamera vertikal über dem Paper Prototype zu montieren.
* Die Usability-Tests haben vor allem kleine Unstimmigkeiten des Redesigns hervorgebracht wie z.B.
  unpassend gewählte Icons. Ansonsten war das Redesign ein voller Erfolg.
* Mit bereits relativ wenig Aufwand kann ein Produkt mit suboptimaler UX deutlich verbessert werden, 
  indem man beim Design von den Zielen des Benutzers ausgeht.
* Um allzu aufwendiges "Basteln" zu verhindern, kann mit zugeschnittenen Post-Its eine 
  vordefinierte Schreibfläche erzeugt werden, welche nach Gebrauch schnell ausgewechselt werden 
  können und nicht einen neuen Ausdruck benötigt. Dies kann aber dazu führen, 
  dass User nur auf die "gelben Zettel" achten und sonstige Interaktionselemente ausser Acht lassen.
  Eine mögliche Lösung dafür wäre die Verwendung von Zetteln, die sich nicht vom Hintergrund abheben.
  Auf dies wurde verzichtet, damit die Benutzer nicht versehentlich auf den darunterliegenden 
  Paperprototype schreiben, wenn sie versehentlich über den (kaum sichtbaren) gleichfarbigen 
  Klebezettel hinausschreiben.
  

Ausblick
========

Nach Abschluss der Projektes werden die Ergebnisse und Vorschläge für neue UIs den Verantwortlichen 
bei Crealogix präsentiert. Ob und wann die Resultate in das Produkt einfliessen, 
steht nicht in der Macht des Projektteams.

Es wäre aber durchaus interessant, Features, welche seit Beginn des Projekts wieder hinzugekommen 
sind, in die neuen Designs zu integrieren. Der Timing-Inspector bietet sich hier an,
welcher eine "Zeitachse" einführt. Hier wurde aber entschieden, über sogenannte Steps 
auf der Zeitachse voranzuschreiten, was wobei es wichtig wäre zu testen, ob dies für Benutzer
verständlich ist.
