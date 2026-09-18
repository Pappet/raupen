# Raupen-Garten

Zahlen-Lernspiel (Zahlzerlegung bis 10) als Progressive Web App.
Läuft nach der Installation offline, Spielstand im localStorage.

## Bedienung
- Raupe an beliebiger Stelle packen und ziehen: ganze Raupe bewegen
- Raupe antippen: wird laut gezählt
- Raupe kurz festhalten (sie wackelt, ✂️ erscheint an der Schnittstelle)
  und dann wegziehen: Raupe teilen – die gegriffene Kugel kommt mit
- Raupe auf eine andere legen: zusammenstecken (max. 10)
- Die Zahl am Blatt antippen: Kugeln zählen im Takt der Stimme
- Passende Raupe aufs Blatt (unten): sie frisst es und wird zum Schmetterling

## Farben
Jede Länge hat eine eigene Farbe (1 rosa, 2 lila, 3 grün, 4 blau, 5 orange,
6 türkis, 7 rot, 8 gelb, 9 braun, 10 dunkelblau). Kugeln ab der 6. haben einen
hellen Ring, damit man z. B. 7 als „fünf und zwei“ sieht.
Farben stehen in `COLORS` in index.html.

## Level (alle 3 Schmetterlinge eins höher)
1. Ziel 2–5, passende Raupe ist dabei
2. Ziel 3–7, zwei Raupen zusammenstecken
3. Ziel 4–9, zusammenstecken oder teilen
4. Ziel 5–10, drei Teile oder teilen

## Veröffentlichen / Installieren / Ändern
Wie bei der Pizzeria: GitHub Pages, in Chrome „App installieren“,
nach Änderungen `VERSION` in `sw.js` hochzählen.

## Spielstand zurücksetzen
Schmetterling-Anzeige oben rechts 3 Sekunden gedrückt halten.
