# FPV Akku-Logbuch

**Live-Demo:** https://grown661.github.io/fpv-battery-log/

LiPo-Akkus sterben an vergessener Lagerung und ungezählten Zyklen – dieses PWA-Logbuch trackt beides, offline und ohne Account.

## Features

- Akkus anlegen mit Name, Zellenzahl (1S–8S), Kapazität und Kaufdatum
- Zyklen-Zähler pro Akku (Flug = +1 Zyklus)
- Status-Tracking: **Voll geladen / Leer / Storage**
- Warnung, wenn ein Akku mehrere Tage voll oder leer herumliegt (Storage-Erinnerung)
- Warnung ab hoher Zyklenzahl (Zustand prüfen)
- **PWA:** installierbar, offline-fähig (Service Worker + Manifest)
- Daten bleiben lokal im Browser (localStorage)

## Stack

Vanilla JavaScript, HTML, CSS, Service Worker – keine Build-Kette, keine Libraries.

## Setup & Start

```
index.html im Browser öffnen – fertig.
```

Für die volle PWA-Funktion (Installieren, Offline-Cache) über einen lokalen Server starten, z. B.:

```
npx serve .
# oder
python -m http.server 8000
```

## Screenshot

_(Screenshot folgt)_
