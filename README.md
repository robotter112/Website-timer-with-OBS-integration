<h1 align="center">
    SC5-Timer
</h1>
<p align="center">
  <p align="center">Smarter Timer für Events</p>
</p>

<h4 align="center">
  <a href="https://sc5countdown.partymc.de">Website</a>
</h4>

<h3 align="center">
</h3>

Ein intelligenter Timer für Spielevents mit der Möglichkeit, ihn in OBS zu integrieren und den Hintergrund mithilfe benutzerdefinierter CSS zu entfernen.

- OBS-Integration
- Keine Google Fonts
- Einfach anpassbar

Bitte beachten Sie, dass sich dieses Projekt noch in der Entwicklung befindet.

Schauen Sie sich die Demo an.

## 📱 Screenshots

<table>
  <tr>
    <td><img alt="SC5 Timer Vorschau" src="img/2025-01-13_08-10.png"/></td>
   </tr>
</table>

## Übersicht

Dieses Repository enthält den Quellcode für eine responsive Countdown-Webseite, die die verbleibende Zeit bis zum SC5 Weihnachts-Event anzeigt. Die Webseite zeigt einen dynamischen Countdown in Tagen, Stunden, Minuten und Sekunden an.

## Features

- Responsives Design für verschiedene Bildschirmgrößen (Desktop, Tablet, Mobil)
- Dynamischer Countdown bis zum festgelegten Datum (24. Dezember 2025, 08:00 Uhr)
- Animiertes Logo mit Schwebeeffekt
- Hintergrundbild im Vollbildmodus
- Halbtransparente Countdown-Box mit Blur-Effekt
- OBS-kompatible CSS-Datei für Streaming-Integration

## Technologien

- HTML5
- CSS3 (mit Flexbox und Animationen)
- JavaScript (Vanilla JS für den Countdown)
- Webp-Bildformat für optimierte Ladezeiten

## Repository-Struktur

- ```/www``` - Enthält alle Dateien der Webseite (HTML, Bilder)
- ```/scripts``` - Enthält die CSS-Datei für OBS-Integration
- ```/img``` - Enthält Vorschaubilder und andere Medien

## Installation

1. Klone das Repository:
   ```
   git clone https://git.fastm.de/Max/SC5-Timer.git
   ```

2. Öffne die ```/www/index.html``` Datei in deinem bevorzugten Webbrowser.

## OBS-Integration

Im Verzeichnis ```/scripts``` befindet sich eine spezielle CSS-Datei, die verwendet werden kann, um den Timer in OBS einzubinden und korrekt auszuschneiden. Füge die Webseite als Browser-Quelle in OBS hinzu und wende die CSS-Datei an, um nur den Timer anzuzeigen.

## Anpassung

### Countdown-Ziel ändern

Um das Zieldatum des Countdowns zu ändern, bearbeite die folgende Zeile in der ```/www/index.html``` Datei:

```javascript
const targetDate = new Date('2025-12-24T08:00:00+01:00');
```

### Styling anpassen

Das Design kann durch Bearbeiten des ```<style>```-Abschnitts in der ```index.html``` Datei angepasst werden. Die Webseite verwendet responsive Breakpoints für verschiedene Bildschirmgrößen:

- Desktop: > 768px
- Tablet: 480px - 768px
- Mobil: < 480px

## 📜 Lizenz

SC5-Timer ist Freie Software: Du kannst sie nach Belieben nutzen, studieren, teilen und verbessern. Insbesondere kannst du sie unter den Bedingungen der AGPL-3.0-Lizenz weiterverbreiten und/oder modifizieren.

