# LFH Template

![Lizenz](https://img.shields.io/badge/License-MIT-blue.svg)
![LaTeX](https://img.shields.io/badge/LaTeX-gray.svg?style=flat&logo=latex)

Diese LaTeX-Vorlage wurde speziell für die Verwendung an der Leibniz-FH entwickelt und bietet eine modulare Struktur für die Erstellung wissenschaftlicher Arbeiten, Berichte und anderer Dokumente.

**Wichtiger Hinweis:** Diese Vorlage erfordert die Kompilierung mit `lualatex` oder `xelatex`. Stellen Sie sicher, dass Arial auf Ihrem System installiert ist (Overleaf unterstützt beide Optionen, [hier](https://www.overleaf.com/read/mxnfzswtrgnc#299745) ein Beispiel).

## Funktionen

* **Modulare Struktur:** Klare Trennung von Deckblatt, Metadaten, Präambel und Inhalt.
* **Anpassbarkeit:** Einfache Anpassung von Metadaten und Dokumenteinstellungen.
* **Benutzerdefinierte Befehle:** Möglichkeit, eigene Befehle und Shortcuts zu definieren.
* **Strukturierte Inhaltsverwaltung:** Separate Ordner für Inhalt, Anhang und zusätzliche Elemente.

## Inhalt des Repositorys

* `main.tex`: Hauptdatei zur Kompilierung des Dokuments.
* `base/Deckblatt.tex`: Datei für das Deckblatt.
* `base/Meta.tex`: Datei für Metadaten (Titel, Autor, Datum, Institution).
* `base/Preamble.tex`: Datei für Paketimporte, Dokumenteinstellungen und Anpassungen.
* `base/Inhalt.tex`: Datei zum Einbinden der Inhaltsdateien.
* `base/Erklaerung.tex`: Datei für die Erklärung/Authentizitätserklärung.
* `base/Sperrvermerk.tex`: Datei für den Sperrvermerk (falls zutreffend).
* `base/Befehle.tex`: Datei für benutzerdefinierte Befehle und Shortcuts.
* `Inhalt/`: Ordner für die Inhaltsdateien.
* `images/`: Ordner für Bilder.

## Erste Schritte

1.  **Beispiel ansehen:** Machen dich mit dem Beispiel vertraut.
2.  **Metadaten anpassen:** Bearbeite die Datei `base/Meta.tex` mit deinen spezifischen Informationen.
3.  **Inhalt erstellen:** Erstelle deine Inhaltsdateien im Ordner `Inhalt/`.
4.  **Inhalt einbinden:** Binden deine Inhaltsdateien in `base/Inhalt.tex` ein.
5.  **Kompilieren:** Kompilieren von `main.tex` mit `lualatex` oder `xelatex`.

## Anpassungsmöglichkeiten

* **Preamble.tex:** Passe die Dokumenteinstellungen, Schriftarten und Paketimporte in dieser Datei an.
* **Befehle.tex:** Definieren eigene Befehle und Shortcuts, um die Dokumenterstellung zu beschleunigen.
* **Inhalt/:** Organisieren deinen Inhalt in logischen Unterordnern für eine bessere Struktur.

## Voraussetzungen

* LaTeX-Distribution (z.B. TeX Live oder MiKTeX)
* `lualatex` oder `xelatex`
* Arial Schriftart installiert


## Beiträge

Beiträge sind willkommen! Wenn du Fehler fiindest oder Verbesserungen vorschlagen möchtest, erstellen bitte ein Issue oder einen Pull Request.
