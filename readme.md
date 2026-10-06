# VIENNA: BLACKOUT

**Autor:** Laurin Kranewitter

Semesterprojekt für Structured Programming im ersten Semester.

## Projektidee

VIENNA: BLACKOUT ist ein geplantes deutschsprachiges Survival-Spiel für die Konsole. Ein fiktiver Stromausfall legt Wien lahm. Der Spieler muss fünf Tage überleben, bis Hilfe eintrifft. Dafür verwaltet er Gesundheit, Energie, Hunger und Durst sowie begrenzte Vorräte an Nahrung, Wasser und Medizin.

Die Stimmung verbindet Überlebensentscheidungen mit Wiener Humor und absurden Situationen. Zufällige Ereignisse bieten teilweise mehrere Antworten: Manche helfen, manche haben einen Haken, und manche sind einfach eine ziemlich schlechte Idee.

## Geplanter Umfang

- Fünf Spieltage mit einem klaren Sieg nach der Rettung und einer Niederlage bei null Gesundheit.
- Sieben Orte: Wohnung als Unterschlupf, Prater, Supermarkt, Apotheke, FH Technikum Wien, Donauinsel und Westbahnhof.
- Vorräte suchen, reisen, essen, trinken, Medizin verwenden, rasten und Inventar ansehen.
- Aktionen verbrauchen Zeit; Reisen und Suchen kosten zusätzlich Energie. Hunger und Durst nehmen mit der Zeit zu.
- Ein überschaubarer Vorrat an Zufallsereignissen mit humorvollen Entscheidungen und Fallen. Folgen bleiben verständlich, damit Entscheidungen mehr als bloßes Raten sind.
- Übersichtliche Konsolenmenüs mit ASCII-Rahmen und Statusbalken.

Es sind kein komplexes Kampfsystem, keine echte Kartensimulation und keine Speicherfunktion vorgesehen.

## Technik

Das bestehende IntelliJ-Projekt ist für Java 8 eingerichtet. Die Umsetzung soll ausschließlich mit der Java-Standardbibliothek, Variablen, einfachen Klassen, Arrays, Methoden, Schleifen und Verzweigungen erfolgen. Es werden keine Collections, Vererbung, abstrakten Klassen, Streams, Lambdas, eigenen generischen Strukturen, GUI-Frameworks oder externen Abhängigkeiten verwendet. Records sind unter Java 8 nicht verfügbar.

## Aktueller Stand und Ausführung

Das Spiel ist noch nicht implementiert. Aktuell enthält `src/Main.java` nur das IntelliJ-Beispielprogramm. Dieses kann in IntelliJ über die `main`-Methode gestartet werden. Die geplanten Funktionen stehen in `features.md`; nach ihrer Umsetzung wird der Status dort aktualisiert.

## Abgabe

Die Abgabe erfolgt entweder als ZIP-Datei des Projekts oder als Textdatei mit dem Link zum Git-Repository, beispielsweise `kranewitter_git_project.txt`. Das Projekt muss `readme.md`, `features.md` und `agents.md` enthalten. Ein fertiges Abgabearchiv oder eine Repository-Linkdatei wird erst erstellt, wenn das Projekt fertig und das Abgabeformat festgelegt ist.
