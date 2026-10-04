# 🐱 Katzen-Schönheitssalon

Ein kleines 2D-Browserspiel: Eine völlig verwahrloste Katze zieht in ein Haus ein und muss
in **Badezimmer, Wohnzimmer und Schlafzimmer** wieder aufgepeppt werden.

**Einfach `index.html` im Browser öffnen – keine Installation, kein Server nötig.**

---

## 🎮 So wird gespielt

Die Katze ist dreckig, verfilzt, hungrig und hat viel zu lange Krallen. Sieben Pflege-Schritte
machen sie wieder schön:

| # | Aufgabe | Raum | Werkzeug |
|---|---------|------|----------|
| 1 | Waschen | 🛁 Badezimmer | Duschgel (Katze vorher in die Badewanne setzen) |
| 2 | Kämmen | 🛁 Badezimmer | Kamm |
| 3 | Krallen kürzen | 🛁 Badezimmer | Schere |
| 4 | Zähne putzen | 🛁 Badezimmer | Zahnbürste |
| 5 | Füttern | 🛋️ Wohnzimmer | Futter |
| 6 | Spielen | 🛋️ Wohnzimmer | Spielball |
| 7 | Schlafen | 🛏️ Schlafzimmer | Katze aufs Bett legen **und** mit dem Kissen zudecken |

**Bonus:** Die Katze antippen (ohne zu ziehen) streichelt sie und bringt Herzen. 💖

### Bedienung

- **Ziehen & ablegen** mit der Maus – oder
- **Antippen**: Werkzeug auswählen, dann die Katze antippen (gut für Tablet & Smartphone)

### Tastenkürzel

| Taste | Funktion |
|-------|----------|
| `1` | Badezimmer |
| `2` | Wohnzimmer |
| `3` | Schlafzimmer |
| `R` | Neustart |
| `M` | Ton an/aus |
| `Esc` | Werkzeugauswahl aufheben |

---

## ✨ Features

- **Drei liebevoll gezeichnete Räume** – Badezimmer mit Badewanne und Wasser, Wohnzimmer mit
  Sofa und Fenster, Schlafzimmer mit Bett und Nachthimmel. Komplett in Canvas 2D gezeichnet,
  keine Bilddateien.
- **Die Katze verändert sich sichtbar**: Die Fellfarbe wechselt von grau-dreckig zu warmem
  Goldbraun, Schmutzflecken und verfilzte Fellbüschel verschwinden, die Krallen werden kürzer.
- **Lebendige Katze**: blinzelt, wedelt mit dem Schwanz und zeigt je nach Stimmung
  verschiedene Gesichter (hungrig, zufrieden, glücklich, erschrocken).
- **Partikeleffekte**: Schaumblasen beim Waschen, Glitzer beim Kämmen und Zähneputzen,
  Krümel beim Fressen, Sterne und Herzen beim Sieg.
- **Kuscheldecke**, die mit dem Zudecken-Fortschritt Stück für Stück höher wandert.
- **Kleine Sounds** direkt per WebAudio erzeugt, abschaltbar.
- **Auf allen Geräten spielbar** – Maus, Touch und Tastatur.

## 🛠️ Technik

Eine einzige HTML-Datei mit eingebettetem CSS und JavaScript. Keine Bibliotheken, keine
Build-Tools, keine externen Requests. Die Grafik entsteht vollständig prozedural im
`<canvas>`-Element.

```
katzen-schoenheitssalon/
└── index.html   ← das komplette Spiel
```

## 🚀 Lokal starten

```bash
git clone https://github.com/<dein-name>/katzen-schoenheitssalon.git
cd katzen-schoenheitssalon
```

Dann `index.html` doppelklicken – fertig.

## 📄 Lizenz

MIT – mach damit, was du willst.
