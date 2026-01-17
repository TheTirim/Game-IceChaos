# Ice Chaos

Ice Chaos is a lightweight single-file endless runner built on the HTML5 canvas. Dodge icy obstacles, survive as long as possible, and watch the speed ramp up over time.

## Features
- Emoji placeholders
- Highscore (localStorage)
- Debug mode
- God Mode
- Slow Motion
- Freeze & Frame Step
- Spawn Test

## Controls
- **W / Arrow Up**: Move up
- **S / Arrow Down**: Move down
- **Space / Enter**: Start / Restart
- **Esc**: Back to menu
- **F3 / D**: Toggle debug overlay
- **G**: Toggle God Mode
- **1 / 2 / 3**: Slow Motion 1.0 / 0.5 / 0.25
- **P**: Freeze
- **O**: Step one frame (when frozen)
- **T**: Spawn test obstacle (debug only)

## How to run
1. Open `index.html` in your browser.
2. If your browser blocks file access or local storage, run a simple local server instead.

## Folder structure
```
/assets/penguin.png
/assets/iceberg.png
/assets/bg.png
```

## Enable sprites later
- Set `USE_SPRITES = true` inside `index.html`.
- Use PNGs with transparent backgrounds for best results.

## Highscore reset
Clear the `iceChaosHighscore` key in your browser storage to reset the highscore.

## TODO
- Background rendering polish
- Real sprite art
- Animations
