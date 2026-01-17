# Ice Chaos

Ice Chaos ist ein leichtgewichtiges Single-File-Endless-Runner-Game auf Basis von HTML5-Canvas. Weiche eisigen Hindernissen aus, überlebe so lange wie möglich und erlebe den stetigen Geschwindigkeitsanstieg.

## Features
- Emoji-Platzhalter
- Highscore (localStorage)
- Debug-Modus
- God Mode
- SlowMo
- Freeze & Frame Step
- Spawn-Test

## Steuerung
- **W / Pfeil hoch**: Nach oben
- **S / Pfeil runter**: Nach unten
- **Space / Enter**: Start / Neustart
- **Esc**: Zurück ins Menü
- **F3 / D**: Debug-Overlay umschalten
- **G**: God Mode umschalten
- **1 / 2 / 3**: SlowMo 1.0 / 0.5 / 0.25
- **P**: Freeze
- **O**: Einzelnes Frame (nur bei Freeze)
- **T**: Spawn-Test (nur Debug)

## Start
1. `index.html` im Browser öffnen.
2. Falls der Browser lokale Dateien oder Storage blockiert, einen lokalen Server nutzen.

## Ordnerstruktur
```
/assets/penguin.png
/assets/iceberg.png
/assets/bg.png
```

## Sprites später aktivieren
- `USE_SPRITES = true` in `index.html` setzen.
- Transparente PNGs werden empfohlen.

## Highscore zurücksetzen
Lösche den Schlüssel `iceChaosHighscore` im Browser-Storage, um den Highscore zurückzusetzen.

## TODO
- Hintergrund ausarbeiten
- Echte Grafiken
- Animationen
