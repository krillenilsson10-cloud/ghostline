# Ghostline

Live sektionstimer för bil och MC – karta, checkpoints och livejämförelse med kompisar.

## Live
https://krillenilsson10-cloud.github.io/ghostline/

## Funktioner
- Livehastighet (km/h), snitt och max
- START / STOPP / SPLIT med historik
- Karta (OpenStreetMap) över hela Sverige – sätt checkpoints var du vill
- GPS-punkter som larmar automatiskt inom 25 m
- Live-rum: skapa en kod och jämför tider i realtid
- Installerbar PWA med offline-stöd

## Installation
Öppna länken i Chrome → menyn → "Installera app" (eller "Lägg till på startskärmen").

## Utveckling
Appen är en enda `index.html` (Leaflet + MQTT inbakat) plus `manifest.webmanifest`,
`sw.js` och ikoner. Ingen backend – realtiden går via en publik MQTT-broker.

---
Byggd med DeepSeek Harness.
