# Ice Chaos

## Description
A fast-paced 2D endless runner where you control a penguin through an icy cave, dodging icebergs and flying snowballs while the speed constantly increases.

## Preview

### Gameplay Video
<video src="video/test.mp4" controls width="800"></video>

### Screenshot
![Gameplay Screenshot](screenshot/screenshot.png)

The gameplay video is stored directly in the repository and embedded using HTML `<video>` for GitHub preview.

## Features
- 2D side-scrolling endless runner
- Stylized cartoon ice cave background
- Penguin player with full 2D movement (up/down/left/right)
- Iceberg spikes spawning from top and bottom (direction-based hitboxes)
- Flying snowball obstacles with diagonal bouncing movement
- Increasing game speed over time (difficulty ramp)
- Fair hitbox system (separate render & collider boxes)
- Highscore system with name entry (stored via localStorage)
- Debug mode with hitbox visualization
- Keyboard-only gameplay
- Persistent highscores
- Built-in imprint below the game

## Controls
### Gameplay
- W / Arrow Up – Move up
- S / Arrow Down – Move down
- A / Arrow Left – Move left
- D / Arrow Right – Move right
- Space / Enter – Start / Restart
- Esc – Return to main menu

### Debug
- F3 or D – Toggle debug overlay
- G – God Mode
- 1 / 2 / 3 – Slow motion levels
- P – Freeze game
- O – Step one frame
- T – Spawn test obstacle

## Assets / Folder Structure
- /assets/bg.png        – Ice cave background
- /assets/penguin.png   – Player sprite
- /assets/iceberg.png   – Iceberg spike (flipped in code)

## How to Run
- Open index.html in a modern browser
- Optional: use a local web server if your browser blocks asset loading

## Highscores
- Stored locally in the browser using localStorage
- Top 10 scores are saved with player name and time
- To reset highscores: clear browser site data

## Imprint
© 2026 theTirim

## TODO
- Animated sprites
- Additional obstacle types
- Sound effects & music
- Mobile/touch support
