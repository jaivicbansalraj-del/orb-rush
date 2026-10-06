[README.md](https://github.com/user-attachments/files/33114779/README.md)
# Orb Rush

A fast 2D arcade survival game that runs in your browser. Collect orbs, dodge enemies, and beat your high score.

## How to play

Move around the arena and collect the glowing orbs. Each orb is worth 10 points. Avoid the enemies, because every hit costs a life. You have 3 lives.

Every 5 orbs you collect, the level goes up: enemies spawn faster, move faster, and a new enemy type joins the arena.

| Thing | What it does |
| --- | --- |
| Teal orb | Collect it for +10 points |
| Red diamond (chaser) | Follows you around the arena |
| Purple ring (bouncer) | Bounces off the walls in straight lines |

## Controls

| Action | Keyboard | Touch screen |
| --- | --- | --- |
| Move | WASD or arrow keys | Drag anywhere |
| Pause / resume | P or Esc | Not available |
| Start / restart | Enter | Tap the button |

Your best score is saved in your browser.

## Run it locally

No install or build step is needed.

1. Download `index.html`.
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge).

## Built with

Plain HTML, CSS, and JavaScript, drawn on an HTML canvas. The whole game is in a single file, with no external libraries or images.

## Customize it

Open `index.html` in a text editor and look for these values:

- Player speed: `maxSp` in the `update` function
- Number of lives: `lives = 3` in the `reset` function
- Orbs per level: `Math.floor(collected / 5)`
- Colors: the `COLORS` object near the top of the script

## License

Free to play, share, and modify.
