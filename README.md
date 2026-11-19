# Atelier

Mobile Web-App (PWA) für abgestimmte Foto-Looks – Schwerpunkt Porträt- und Modelfotografie.
Läuft komplett im Browser, Fotos verlassen das Gerät nicht.

**Live:** https://insta.micana.de

## Funktionen
- 42 Looks in den Kategorien Signature, Neutral, Porträt, Fashion, Film und S/W
- Hautschutz: Hauttöne bleiben natürlich, Haut glätten mit Kantenschutz
- Farbsteuerung pro Farbbereich (Sättigung, Helligkeit, Farbton)
- Eigene Looks speichern, Favoriten
- Stapelbearbeitung: bis zu 30 Fotos mit gleichem Look, gemeinsamer Export
- Retusche-Pinsel: Aufhellen, Abdunkeln, Glätten, Radierer
- Feed-Vorschau (3er-Raster, bleibt gespeichert, bestehende Posts hinzufügbar)
- Rückgängig/Wiederholen, Vorher-Vergleich (Bild gedrückt halten)
- Installierbar und offline nutzbar (Service Worker)

## Installation am iPhone
Seite in Safari öffnen → Teilen → „Zum Home-Bildschirm“.

## Aufbau
- `index.html` – komplette App (HTML, CSS, JS in einer Datei)
- `sw.js` – Offline-Cache
- `manifest.webmanifest`, `icons/` – Installation als App
- `CNAME` – eigene Domain für GitHub Pages

Bei Änderungen an der App die Cache-Version in `sw.js` erhöhen (`atelier-v2` …).
