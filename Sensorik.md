# Sensorik für FAS

## Ultraschall

- basiert auf dem piezoelektrischem Effekt
- Arbeitsbereich: 40-50kHz
    - Kompromiss zwischen Empfindlichkeit, Reichweite etc. und Robustheit gegenüber Fremdgeräuschen (höhere Frequenzen werden stärker durch die Luft gedämpft, tiefere Frequenzen bringen Umgebungsgeräusche mit sich, <20kHz menschliches Hören)
- wird in nähe seiner Resonanz betrieben und wird entsprechend so gefertigt
- Beschaltung kompensiert Temperaturabhängigkeit der Kapazität damit die Resonanzfrequenz stabil bleibt
- 300 µs Sendedauer, 700µs Ausklingen
- Temperatur verändert die Schallgeschwindigkeit / Umgebungsfeuchte sonst nur marginal
- mit Trilateration ist eine Positionsbestimmung von Objekten neben dem Fahrzeug möglich
- Kreuzechos ermöglichen die Unterscheidung zwischen Wand und Punkt