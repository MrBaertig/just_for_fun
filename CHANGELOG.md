# Changelog – MarkItDown Drop

Hier sind alle bisher dokumentierten Versionen von MarkItDown Drop zusammengefasst. Die neueste Version steht oben.

## [1.6.2](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.6.2) – 17. August 2026

### Vorschau und Validierungsbericht für Markdown nach Excel

- Erkannte Tabellen mit Blattname, Zeilen- und Spaltenzahl vor dem Speichern anzeigen
- Künftigen Datentyp je Spalte ausweisen
- Blattnamen in der Vorschau ändern und einzelne Tabellen abwählen
- Zeilen mit zu wenigen oder zu vielen Spalten melden
- Gemischte Spaltenwerte, gekürzte Blattnamen, leere Überschriften und leere Tabellen melden

### Frei skalierbare Fenster

- Hauptfenster, Einstellungen, Excel-Vorbereitung und Vorschau vergrößerbar
- Kacheln wachsen mit dem Fenster, Mindestgrößen verhindern zerdrückte Ansichten
- Größe und Position von Hauptfenster, Einstellungen und Hilfe bleiben erhalten

### Tastatur, VoiceOver und Hilfe

- Befehl-1 bis Befehl-3 für die drei Konvertierungswege, Befehl-R für die Installationsprüfung
- Neue Menüs für Ablage, Fenster und Hilfe
- Sinnvolle Fokusreihenfolge über die Kacheln zur Ersteinrichtung
- Eindeutige Beschriftungen für die drei gleichnamigen Auswahlknöpfe
- Gesperrte Knöpfe nennen den Grund
- Integrierte Hilfe mit Schnellstart, Ersteinrichtung, Konvertierung, Datenschutz, Updates und Fehlerhilfe

## [1.6.1](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.6.1) – 17. August 2026

### Verständlichere Fehlermeldungen

- Letzte Protokollzeilen direkt im Fehlerdialog anzeigen
- Protokoll auf Knopfdruck aus dem Dialog heraus öffnen
- Beschädigte oder falsch benannte Excel-Dateien verständlich melden
- Fehlende Dateien, gesperrte Dateien und übergebene Ordner klar unterscheiden
- Nach einer abgebrochenen Ersteinrichtung den Zustand automatisch neu prüfen

### Deutlicherer Hinweis auf die Ersteinrichtung

- Konkret benennen, welche Bestandteile fehlen
- Text und Pfeil kompakt über dem Knopf statt quer über die Startkacheln führen
- Pfeilspitze zuverlässig auf den Knopf ausrichten

## [1.6.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.6.0) – 17. August 2026

### Ersteinrichtung prüft zuerst und installiert nur Fehlendes

- Vollständiger Vorabcheck von Homebrew, Python 3.13, Git, Quellordner, Python-Umgebung, Paketen und MarkItDown-Befehl
- Installation ausschließlich für Fehlendes oder Unpassendes, bei vollständiger Einrichtung nach etwa einer Sekunde beendet
- Benötigte Pakete aus den Paketdaten von MarkItDown selbst ermitteln, damit die Liste nicht veraltet
- Jeden Schritt als vorhanden, installiert, repariert oder übersprungen ausweisen
- Aktualisieren und Reparieren bleiben den Wartungsbuttons vorbehalten
- Homebrew aktualisiert bei der Einrichtung nicht mehr die gesamte Formelsammlung

### Prüfung ohne Terminalfenster

- Prüfung läuft direkt in der App, Terminalfenster nur noch für tatsächliche Installationen
- Automatische Prüfung beim Programmstart und beim Zurückwechseln zur App
- Rückfrage vor der Installation benennt die fehlenden Bestandteile einzeln
- Nach der Einrichtung meldet das Fenster, wie viel ergänzt und wie viel bereits vorhanden war

### Deutlicher Hinweis bei unvollständiger Installation

- Ersteinrichtungs-Button orange hervorheben und kurz pulsieren lassen
- Fenster abdunkeln und mit beschriftetem Pfeil auf den Button zeigen
- Startkacheln sperren, solange die Einrichtung unvollständig ist

## [1.5.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.5.0) – 17. August 2026

### Kopfzeile je Tabellenblatt auswählen

- Tatsächliche Kopfzeile je Tabellenblatt individuell festlegen
- Zeilennummer und Vorschau erkannter Zellinhalte im Auswahlmenü anzeigen
- Spaltennamen und Beispielwerte nach der Auswahl unmittelbar aktualisieren
- Zeilen oberhalb der Kopfzeile nur in der temporären Arbeitskopie entfernen
- Auswahl mit Anonymisieren, Löschen und Tabellenblattauswahl kombinieren
- Nur tatsächlich belegte Zellen analysieren und aufgeblähte Excel-Bereiche schnell verarbeiten
- Große Analyseergebnisse über temporäre Dateien übertragen und Pipe-Blockaden verhindern

Vollständige Hinweise: [changelogs/1.5.0.md](changelogs/1.5.0.md)

## [1.4.1](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.4.1) – 17. August 2026

### Reparierte Ersteinrichtung auf neuen Macs

- Python 3.13 gezielt über Homebrew installieren und für die App-Umgebung verwenden
- Inkompatible Python-3.14-Umgebungen automatisch erkennen und ersetzen
- MarkItDown nur mit den benötigten PDF-, Word-, PowerPoint-, Excel-, Outlook- und Audio-Erweiterungen installieren
- Problematische optionale YouTube- und Azure-Abhängigkeiten ausschließen
- Homebrew-Downloads bei vorübergehenden Netzwerkfehlern automatisch wiederholen
- Bei HTTP 429 einen privaten Hotspot und den offiziellen Homebrew-PKG-Installer als Alternativen nennen
- MarkItDown-Aktualisierung und Reparatur ebenfalls mit Python 3.13 ausführen
- Updatefeed als GitHub-Release-Datei ausliefern, um HTTP-429-Fehler des Raw-Endpunkts zu vermeiden

Vollständige Hinweise: [changelogs/1.4.1.md](changelogs/1.4.1.md)

## [1.4.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.4.0) – 16. August 2026

### Neue Startansicht und Rückkonvertierung

- Drei getrennte Kacheln für „Excel → Markdown“, „Markdown → Excel“ und „Anderer Dateityp“
- Drag-and-drop und eigene Dateiauswahl je Arbeitsablauf
- Markdown-Tabellen als formatierte `.xlsx`-Dateien exportieren
- Markdown-Überschriften automatisch als Tabellenblattnamen verwenden
- Mehrere Tabellen sowie doppelte und Excel-ungültige Blattnamen sicher behandeln
- Zahlen und Datumswerte erkennen, führende Nullen jedoch erhalten
- Filter, fixierte Kopfzeilen, passende Spaltenbreiten und dezente Tabellenformatierung

Vollständige Hinweise: [changelogs/1.4.0.md](changelogs/1.4.0.md)

## [1.3.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.3.0) – 16. August 2026

### Neuer Excel-Vorbereitungsdialog

- Excel-ähnlicher Tabellenblattfilter mit Mehrfachauswahl
- Abgewählte Tabellenblätter verschwinden sofort aus der Bearbeitung
- Aufklappbare Tabellenblattbereiche für eine ruhigere Übersicht
- Bis zu zwei Beispielwerte je Spalte
- Sammelaktionen direkt in den Tabellenblatt-Kopfzeilen
- Tabellenblattbereiche oben und ohne unnötigen Leerraum ausrichten
- Live-Zusammenfassung für anonymisierte und gelöschte Spalten
- Optionale bereinigte Excel-Kopie unter „Weitere Optionen“
- Kompakte Aktionsleiste und korrekte Farben in heller und dunkler Darstellung

Vollständige Hinweise: [changelogs/1.3.0.md](changelogs/1.3.0.md)

## [1.2.0](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.2.0) – 16. August 2026

### Erweiterte Excel-Aufbereitung

- Alle Tabellenblätter übernehmen oder nur einzelne auswählen
- Jede Spalte individuell behalten, anonymisieren oder vollständig löschen
- Nicht ausgewählte Tabellenblätter aus der temporären Arbeitskopie entfernen
- Bereinigte Excel-Datei standardmäßig nur temporär für Markdown verwenden
- Optional eine zusätzliche bereinigte Excel-Kopie speichern
- Warnung bei Formeln oder externen Verknüpfungen vor dem Excel-Export
- Originaldatei bleibt in jedem Fall unverändert
- DMG mit gestaltetem Installationsfenster, Pfeil und „Programme“-Verknüpfung ergänzt

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
