# Alexander Wilhelm – Installierbare Handy-App (PWA)

## Wichtig vorab
Auch wenn du keine „Homepage“ willst: Eine PWA braucht einen HTTPS-Link (eine Adresse), damit sie installierbar ist.
Das kann aber ein *neutraler App-Link* sein (z. B. Netlify/Vercel), ohne klassische Webseite.

## Schnellste Veröffentlichung ohne eigene Website (Netlify Drop)
1) Gehe zu Netlify ("Sites" → "Deploy manually")
2) Entpacke diese ZIP
3) Zieh den Ordner-Inhalt per Drag&Drop in Netlify (Deploy)
4) Du bekommst sofort einen Link wie: https://xyz.netlify.app
5) Diesen Link nutzt du für QR-Code & Installation

## Installation
- Android: Link öffnen → „Zum Startbildschirm hinzufügen“
- iPhone: Safari → Teilen → „Zum Home-Bildschirm“

## QR-Code
In der ZIP ist ein Platzhalter-QR: qr-placeholder.png
Sobald du deinen finalen Link hast, kann ich dir den finalen QR erzeugen.

## Dateien
- index.html
- manifest.json
- sw.js
- icons/icon-192.png, icons/icon-512.png
