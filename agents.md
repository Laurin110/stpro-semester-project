# Anweisungen für AI-Coding-Agents

## Kursvorgabe

> "The project should use structured programming in Java including records or simple classes. No abstractions, inheritance, Collections or other higher level Java features may be used."

Dies ist ein Structured-Programming-Projekt im ersten Semester. Der Code muss von einem Studienanfänger verstanden und im Unterricht erklärt werden können. Die einfache Struktur darf nicht durch fortgeschrittene Java-Techniken ersetzt werden.

## Technische Regeln

- Die bestehende Konfiguration verwendet Java 8. Keine Records oder neuere Java-Syntax verwenden, solange keine ausdrücklich genehmigte Versionsänderung vorliegt.
- Variablen, primitive Datentypen, Strings, Arrays, Methoden, `if`/`else`, `switch`, `for` und `while` bevorzugen.
- Einfache Klassen nur einsetzen, wenn sie die Verständlichkeit verbessern. Keine Vererbung, Interfaces als eigene Abstraktionsschicht, abstrakten Klassen oder komplexe objektorientierte Architektur einführen.
- Keine Collections wie `ArrayList`, `List`, `HashMap`, `Map` oder `Set`. Keine Streams, Lambdas, Generics oder Design Patterns verwenden.
- Nur die Java-Standardbibliothek nutzen; einfache Konsoleneingabe und Zufallszahlen sind zulässig. Keine externen Bibliotheken, Frameworks, Datenbanken, APIs oder Netzwerkzugriffe hinzufügen.
- Keine Swing- oder JavaFX-Oberfläche erstellen. Die Darstellung erfolgt mit normaler Konsolenausgabe und robusten ASCII-Zeichen.

## Projektkonventionen

- Vor Änderungen bestehende Dateien und die IntelliJ-Konfiguration prüfen. Nützlichen Code anpassen und keine Dateien blind ersetzen oder löschen.
- Einstiegspunkt ist `src/Main.java`. Das Projekt muss ohne zusätzliche Abhängigkeiten direkt aus IntelliJ ausführbar bleiben.
- Mehrere überschaubare Methoden mit klaren Aufgaben verwenden, statt alle Abläufe in `main` zu schreiben.
- Verständliche englische Variablen- und Methodennamen verwenden; Spieltexte und Projektdokumentation sind auf Deutsch.
- Nur hilfreiche Kommentare schreiben, etwa zur Spielregel oder zu einer nicht offensichtlichen Berechnung.
- Menüeingaben auf ungültige Werte prüfen. Statuswerte und Vorräte dürfen ihre festgelegten Grenzen nicht überschreiten.
- Humor und Fallen dürfen vorkommen; wichtige Regeln und die Auswirkungen von Entscheidungen müssen verständlich bleiben.
- Umfang begrenzen: fünf Tage, sieben Orte, vier Statuswerte, drei Vorratsarten und einfache Zufallsereignisse. Kein komplexes Kampf-, Karten- oder Speichersystem ergänzen.

## Dokumentation und Prüfung

- `readme.md` beschreibt das Projekt, den tatsächlichen Entwicklungsstand und den Autor Laurin Kranewitter.
- `features.md` enthält nummerierte Funktionen. Geplante und implementierte Funktionen klar unterscheiden und den Status mit jeder Umsetzung aktualisieren.
- Vor Abschluss einer Codeänderung kompilieren und relevante Spielabläufe prüfen, insbesondere ungültige Eingaben, Vorratsverbrauch, Tageswechsel sowie Sieg und Niederlage.
- Aktueller Auftrag: nur Dokumentationsdateien erstellen. Java-Code erst nach einem entsprechenden weiteren Auftrag implementieren.
