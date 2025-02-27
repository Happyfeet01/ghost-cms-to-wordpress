# Ghost to WordPress WXR Converter

## Einleitung
Dieses Python-Skript konvertiert eine **Ghost CMS JSON-Exportdatei** in eine **WordPress WXR-Datei**, die direkt in WordPress importiert werden kann. Es extrahiert Beiträge, Bilder und Metadaten und formatiert sie in das WXR-Format.

## Features
- **Konvertierung von Ghost JSON nach WordPress WXR**
- **Extraktion von Bild-URLs aus Artikel-HTML**
- **Kompatibilität mit dem WordPress-Importer**

## Voraussetzungen
- **Python 3**
- **Benötigte Bibliotheken:**
  ```sh
  pip install beautifulsoup4 requests
  ```

## Installation
1. Klone das Repository oder lade das Skript herunter:
   ```sh
   git clone https://github.com/dein-repo/ghost-to-wordpress.git
   cd ghost-to-wordpress
   ```
2. Installiere die Abhängigkeiten:
   ```sh
   pip install -r requirements.txt
   ```

## Nutzung
Führe das Skript mit folgender Syntax aus:
```sh
python ghost_to_wordpress.py dein-ghost-export.json wordpress-import.wxr
```
- `dein-ghost-export.json` → Pfad zur Ghost JSON-Exportdatei
- `wordpress-import.wxr` → Name der generierten WXR-Datei

## WordPress-Import
1. Gehe in dein WordPress-Dashboard unter **Werkzeuge → Daten importieren**.
2. Installiere den **WordPress-Importer** (falls nicht vorhanden).
3. Lade die erstellte **wordpress-import.wxr** hoch und starte den Import.

## Lizenz
Dieses Projekt ist unter der **MIT-Lizenz** lizenziert.

