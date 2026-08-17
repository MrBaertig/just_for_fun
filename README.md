# MarkItDown Drop – Releases

Öffentliche Downloads und Updatefeed für **MarkItDown Drop**.

Aktuelle Version: **1.4.1** – [Release und Download](https://github.com/MrBaertig/just_for_fun/releases/tag/v1.4.1)

Der Quellcode der App ist nicht Bestandteil dieses Repositorys. Hier werden ausschließlich fertige Versionen, Versionshinweise und der von Sparkle verwendete Updatefeed veröffentlicht.

## Neu in Version 1.4.1

- Python 3.13 wird für MarkItDown fest verwendet
- Bereits angelegte inkompatible Python-3.14-Umgebungen werden automatisch ersetzt
- Nur die von der App benötigten Datei-Erweiterungen werden installiert
- Problematische optionale YouTube- und Azure-Abhängigkeiten entfallen
- Homebrew-Downloads werden bei Netzwerkfehlern automatisch wiederholt
- HTTP-429-Probleme werden verständlich erklärt und mit Alternativen versehen

Vollständige Hinweise: [changelogs/1.4.1.md](changelogs/1.4.1.md)

## Versionshistorie

Der vollständige [Changelog](CHANGELOG.md) enthält alle dokumentierten Versionen ab 1.0.1. Zusätzlich liegt für jede Version eine eigene Datei im Ordner [`changelogs`](changelogs).

## Installation

1. Die aktuelle DMG-Datei unter **Releases** herunterladen und öffnen.
2. Im gestalteten Installationsfenster **MarkItDown Drop** entlang des Pfeils auf **Programme** ziehen.
3. Beim ersten Start kann macOS wegen der fehlenden Apple-Notarisierung eine Sicherheitsfreigabe verlangen.

Alternativ steht weiterhin eine ZIP-Datei bereit. Das ZIP wird außerdem von Sparkle für automatische Updates verwendet.

Ab Version 1.0.2 kann die App spätere Versionen automatisch suchen, kryptografisch prüfen und installieren.

© 2026 Kevin Stegmiller
