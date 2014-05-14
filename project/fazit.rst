=====
Fazit
=====

* Verbesserungen
* Wichtigste Ergebnisse / Erkenntnisse
* Wichtigste Fehler (bestätigt / nicht bestätigt / neue)
* wie weit sind wir?
* was haben wir angeschaut der ganzen app (Ausblick)
* lessions learned
* Müsste man das redesign noch mal machen nachdem was wir gelernt haben bei den Tests der Redesigns?
* Was hat sich bewährt während dem Prototyping?


Verbesserungen
==============

Modul / Seiten erstellen
------------------------

Die komplexen und für den Benutzer teilweise unverständlichen Vorgänge zum Erstellen eines neuen 
Modules konnte mit einem massiv verbesserten Prozess ersetzt werden, 
welcher den Benutzer verständlich führt, ihm jedoch auch die Möglichkeiten offen lässt, abzukürzen.

Weiterhin konnte der Benutzer bisher in Abläufen Elemente auswählen, welche im aktiven Kontext keinen Sinn ergaben, was im besten Fall zu Fehlermeldungen führte, teilweise aber dem User nicht gemeldet wurde. Neu werden dem Benutzer nur noch Elemente angezeigt, 
die er auch wirklich benutzen kann.

Dem Benutzer werden nur noch die Controls und Informationen angezeigt, 
die er wirklich benötigt und die er auch benutzen kann. 
Insbesondere nach dem Start zeigte CLX.Stage dem Benutzer alle Controls der Applikation, 
obwohl dieser noch keine Seiten angelegt oder geladen hatte und entsprechend die Controls für Inhalte nicht 
benutzen konnte.

Das Erstellen von Kapiteln und Seiten wurde in einem Assistenten zusammengefasst. 
Der Benutzer muss nicht mehr technische Unterscheidungen treffen, 
die ihn möglicherweise verwirren, sondern wählt im Assistent aus, was er benötigt. Zusätzlich wird hier dem Benutzer neu die Möglichkeit angeboten, verschiedene Beispielinhalte in die Seiten einzufügen oder nicht. Bisher wurde immer ein Beispielinhalt erstellt, was für erfahrene Benutzer eine Hürde darstellt, da jedes Mal der Inhalt gelöscht werden musste.

Insbesondere die Unterscheidung der einzelnen Fragetypen stellte Benutzer vor enorme 
Herausforderungen, da sie z.T. den Unterschied zwischen den einzelnen Fragetypen gar 
nicht verstanden. Neu passen sich die Fragetypen automatisch der Auswahl des Benutzers an, 
sodass er sich nicht im Voraus festlegen muss.


Inhalte Erstellen
-----------------

Einstellungen für die Seite und Eigenschaften von Inhaltselementen waren bei CLX.Stage an 
verschiedenen Orten untergebracht: Eigenschaften von Inhaltselementen in einer Toolbar 
oberhalb der Seite und Seiteneigenschaften sowie Einstellungen zu den Fragetypen in einer Sidebar. 
Der Benutzer musste genau wissen, was er wo findet. Neu befinden sich alle 
Eigenschaften in einer Sidebar und werden abhängig vom ausgewählten Element und dem aktiven Kontext angezeigt.

Insbesondere das Erstellen und Bearbeiten von Fragen war für Benutzer ziemlich unverständlich, 
da die Editoren oft Elemente anzeigten, die der Benutzer gar nicht brauchte. 
Zudem war oft nicht klar, wo eine bestimmte Aktion zu finden war. 
Neu können einfache Operationen wie das Hinzufügen von Antworten inline im Element 
durchgeführt werden, alle Einstellungen befinden sich in der Sidebaar.


Usability Test Resultate
========================

Die Resultate der Usability Tests zeigten, das das neue UI die Probleme des alten UI's behoben.
Keiner der Tester scheiterte in seinem Auftrag. Alle konnten ihr Ziel erreichen.

Während den Tests sind auch einige verbesserungswürdige Punkte aufgetaucht. 
So enthielt das neue UI einige Icons, welche die Benutzer verwirrten.

Auch über den Systemstatus waren sich die Benutzer nicht immer im klaren. Dies ist vor allem auf 
die Unterschiede des Papier-Prototyp gegenüber einem richtigen UI zurückzuführen, da der Papier-Prototyp 
komplexe Zustände wie Selektion, Hover oder die Unterscheidung Icons/Buttons/Formularelemente nicht
immer verwechslungsfrei wiedergab.

Auf das Redesign zurückzuführende Probleme wurden für den finalen UI-Entwurf noch korrigiert.


Tools & Support
===============

Balsamiq Mockup
---------------
Als Mockup Tool wurde "Balsamiq Mockup" verwendet. Balsamiq eignet sich gut als Mockup Tool. 
User Interface drafts lassen sich schnell und einfach zusammenklicken. 
Als Prototyping Tool ist Balsamiq allerdings eher ungeeignet. Es lassen sich zwar Links zwischen einzelnen Mockups setzen, 
so dass ein Navigieren zwischen Mockups möglich ist, allerdings lassen sich interaktive Elemente wie Menüs oder Formularelemente nicht bedienen.
Somit wäre es erforderlich, dass für jeden Zustand von interaktiven Elementen das Mockup kopiert und angespasst würde, was bereits bei Änderungen am Layout sehr umfassende Anpassungen an vielen Mockups erfordert. 

Will man das Mockup auch für Prototyping verwenden, so ist man mit einem HTML Mockup oder einem anderen Tool besser bedient als Balsamiq.


Paper Prototyping vs. Tool Prototyping
--------------------------------------

Nach unseren Erfahrungen eignet sich Paper Prototyping nur noch bedingt zum Testen von Prototypen, 
da Paper Prototyping die heute üblichen interaktiven Elemente nicht repräsentativ wiedergeben kann.
Insbesondere Scroll-Elemente, Hover- und Active-Zustände, Markierungen, 
Animationen und interaktive Statussymbole können durch Paper Prototypes gar nicht oder nur mit sehr grossem Aufwand ansatzweise abgedeckt werden.





