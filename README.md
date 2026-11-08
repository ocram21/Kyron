# Kyron

Eine mobile Übungsfläche für Schiebetechnik. Die App läuft ohne Build-Schritt und speichert Boards lokal im Browser.

## Lokal ansehen

Die App benötigt einen lokalen Webserver, damit Manifest und Offline-Speicher funktionieren. Im Projektordner:

```sh
python3 -m http.server 8000
```

Dann `http://localhost:8000/Kyron.html` öffnen.

## Auf dem Handy installieren

Die veröffentlichte HTTPS-Seite auf dem Handy öffnen und im Browser „Zum Home-Bildschirm“ beziehungsweise „Installieren“ wählen. Die App ist für eine hochkant genutzte, mobile Ansicht ausgelegt und kann nach dem ersten Laden offline geöffnet werden.

## GitHub Pages veröffentlichen

Das Repository ist für GitHub Pages vorbereitet. Die Veröffentlichung wird manuell über **Actions → Kyron zu GitHub Pages → Run workflow** gestartet.

## Projektdateien

- `Kyron.html` – eigentliche App
- `index.html` – Weiterleitung auf `Kyron.html` für den Pages-Einstieg
- `manifest.webmanifest` – Installationsname, Startadresse und Symbole
- `sw.js` – App-Shell für die Offline-Nutzung
- `icons/` – Symbole für Android, iOS und maskierbare Launcher
