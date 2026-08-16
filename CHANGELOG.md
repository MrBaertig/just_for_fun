# Changelog – MarkItDown Drop

Hier sind alle bisher dokumentierten Versionen von MarkItDown Drop zusammengefasst. Die neueste Version steht oben.

## [1.2.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.2.0) – 16. August 2026

### Erweiterte Excel-Aufbereitung

- Alle Tabellenblätter übernehmen oder nur einzelne auswählen
- Jede Spalte individuell behalten, anonymisieren oder vollständig löschen
- Nicht ausgewählte Tabellenblätter aus der temporären Arbeitskopie entfernen
- Bereinigte Excel-Datei standardmäßig nur temporär für Markdown verwenden
- Optional eine zusätzliche bereinigte Excel-Kopie speichern
- Warnung bei Formeln oder externen Verknüpfungen vor dem Excel-Export
- Originaldatei bleibt in jedem Fall unverändert

Die Markdown-Datei enthält dadurch nur die ausgewählten Tabellenblätter und benötigten Spalten.

Vollständige Hinweise: [changelogs/1.2.0.md](changelogs/1.2.0.md)

## [1.1.1](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.1.1) – 16. August 2026

### Excel-Anonymisierung

- Spaltenüberschriften aus `.xlsx`-Dateien vor der Konvertierung anzeigen
- Mehrere Spalten aus mehreren Tabellenblättern auswählen
- Inhalte ausgewählter Spalten in einer temporären Kopie durch `anonym` ersetzen
- Originaldatei unverändert lassen und temporäre Kopie anschließend löschen
- OpenPyXL ausdrücklich bei Einrichtung, Aktualisierung und Reparatur installieren

Vollständige Hinweise: [changelogs/1.1.1.md](changelogs/1.1.1.md)

## [1.1.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.1.0) – 16. August 2026

### Einstellungen und Stapelverarbeitung

- System-, helle und dunkle Darstellung
- Frei wählbarer Standard-Speicherort
- Markdown-Datei nach der Konvertierung öffnen oder im Finder anzeigen
- Bei vorhandenen Dateien nachfragen, automatisch nummerieren oder überschreiben
- Mehrfachauswahl und Drag-and-drop mehrerer Dateien
- Gemeinsamer Zielordner oder einzelne Speicherabfragen bei Stapeln
- Optionale Abschlussbenachrichtigungen
- Installationsstatus für Python, MarkItDown und Git
- MarkItDown aktualisieren und Python-Umgebung reparieren
- Protokollanzeige und Zurücksetzen der Einstellungen

Vollständige Hinweise: [changelogs/1.1.0.md](changelogs/1.1.0.md)

## [1.0.2](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.0.2) – 16. August 2026

### Automatische Updates

- Sparkle 2.9.5 für automatische Updateprüfungen integriert
- Automatische Downloads und Installationen in den Einstellungen ergänzt
- Universelle App für Apple Silicon und Intel erstellt
- Updates mit einer kostenlosen EdDSA-Signatur abgesichert
- Ersteinrichtung für Homebrew, Python und Microsoft MarkItDown beibehalten

Dies war die erste öffentlich veröffentlichte Version mit eingebauter Updatefunktion.

Vollständige Hinweise: [changelogs/1.0.2.md](changelogs/1.0.2.md)

## 1.0.1 – 16. August 2026

### Erste dokumentierte App-Version

- Native macOS-App mit Drag-and-drop und Dateiauswahl
- Lokale Konvertierung über Microsoft MarkItDown
- macOS-Speicherdialog für erzeugte Markdown-Dateien
- Eigene Ersteinrichtung für Homebrew, Python, Git und MarkItDown
- Helle und dunkle Darstellung
- Eigenes App-, Finder- und Dock-Icon
- Über-Dialog mit Autor Kevin Stegmiller

Version 1.0.1 wurde nicht als öffentliches GitHub-Release verteilt. Die öffentliche Update-Historie beginnt mit Version 1.0.2.

Vollständige Hinweise: [changelogs/1.0.1.md](changelogs/1.0.1.md)
