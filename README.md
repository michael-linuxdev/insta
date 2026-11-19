# Atelier

Mobile Web-App (PWA) für abgestimmte Foto-Looks – Schwerpunkt Porträt- und Modelfotografie.
Läuft komplett im Browser, Fotos verlassen das Gerät nicht.

**Live:** https://insta.micana.de

## Funktionen
- 82 Looks: Signature, Neutral, 5 Pakete (Studio Skin, Summer & Sea, Quiet Luxury, Night & City, Film & Soft), Porträt, Fashion, Film, S/W – plus Vorschläge passend zum Foto
- Hautschutz, Haut glätten, Farbsteuerung pro Farbbereich
- Eigene Looks speichern, als Link teilen, Backup/Import; Favoriten
- Stapelbearbeitung (bis 30 Fotos), eigener Look pro Foto, Stapel angleichen
- Retusche: Reparieren, Aufhellen, Abdunkeln, Glätten, Radierer – mit Zoom
- Feed planen (Drag & Drop), Vorher/Nachher-Bild, Look als .cube-LUT für Videos
- Export Feed (1080 px) oder Original; Sitzung bleibt nach dem Schließen erhalten
- Schnelle Vorschau per WebGL, installierbar und offline nutzbar

## Installation am iPhone
Seite in Safari öffnen → Teilen → „Zum Home-Bildschirm“.

## Aufbau
- `index.html` – komplette App (HTML, CSS, JS in einer Datei)
- `sw.js` – Offline-Cache
- `manifest.webmanifest`, `icons/` – Installation als App
- `CNAME` – eigene Domain für GitHub Pages

Bei Änderungen an der App die Cache-Version in `sw.js` erhöhen (`atelier-v2` …).
