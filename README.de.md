# Ice Chaos

## Beschreibung
Ein schnelles 2D-Endlos-Runner-Spiel, in dem ein Pinguin durch eine Eishöhle gesteuert wird. Eisberge und fliegende Schneebälle müssen umgangen werden, während die Geschwindigkeit stetig steigt.

## Features
- 2D Side-Scrolling Endless Runner
- Cartoon-Eishöhlen-Hintergrund
- Pinguin mit voller 2D-Bewegung (hoch/runter/links/rechts)
- Eisberg-Spikes von oben und unten (richtungsabhängige Hitboxen)
- Fliegende Schneebälle mit diagonaler Bewegung
- Stetig steigende Spielgeschwindigkeit (Difficulty-Ramp)
- Faires Hitbox-System (Renderbox ≠ Kollisionsbox)
- Highscore-System mit Namenseingabe
- Debug-Modus mit Hitbox-Anzeige
- Tastatur-Steuerung
- Persistente Highscores (localStorage)
- Impressum unter dem Spiel

## Steuerung
### Spiel
- W / Pfeil hoch – Nach oben
- S / Pfeil runter – Nach unten
- A / Pfeil links – Nach links
- D / Pfeil rechts – Nach rechts
- Leertaste / Enter – Start / Neustart
- Esc – Zurück ins Hauptmenü

### Debug
- F3 oder D – Debug-Overlay
- G – God Mode
- 1 / 2 / 3 – Zeitlupe
- P – Spiel pausieren
- O – Einzelbild-Schritt
- T – Test-Hindernis spawnen

## Ordnerstruktur / Assets
- /assets/bg.png        – Hintergrund (Eishöhle)
- /assets/penguin.png   – Spieler-Sprite
- /assets/iceberg.png   – Eisberg-Spike (im Code gedreht)

## Start
- index.html im Browser öffnen
- Optional: lokalen Webserver nutzen, falls Assets nicht laden

## Highscores
- Speicherung im Browser (localStorage)
- Top-10-Liste mit Name und Zeit
- Zurücksetzen durch Löschen der Browser-Daten

## Impressum
© 2026 theTirim

## Lizenz
Veröffentlicht unter der MIT-Lizenz. Namensnennung erforderlich – bitte den Copyright-Hinweis beibehalten und "theTirim" nennen.

## TODO
- Animationen
- Weitere Hindernisse
- Soundeffekte & Musik
- Mobile-Unterstützung
