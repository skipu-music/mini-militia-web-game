# Mini Militia — Survival (Web)

A browser-playable build of the JavaScript/CSS Mini Militia survival game supplied in the uploaded ZIP.

## Play

[Play the game on GitHub Pages](https://skipu-music.github.io/mini-militia-web-game/).

Controls: **W/A/S/D** to move, **mouse** to aim, and **left-click** to fire. The game is designed around a keyboard and mouse. Browsers may keep audio muted until the first user interaction.

## Source and licensing

The supplied project is preserved at [`mini-militia-master/`](mini-militia-master/) with all of its original files and paths. The small [`game/`](game/) folder contains only the HTML, CSS, JavaScript and runtime assets published to Pages; unrelated IDE metadata, Photoshop working files and sample artwork are not included in the hosted artifact. The hosted copy handles blocked audio autoplay gracefully; the uploaded original source is unchanged.

See [`LICENSE.md`](LICENSE.md) for the included GPLv3 license. This is an unofficial JavaScript/CSS project, not the official mobile game.

## Deployment

`.github/workflows/pages.yml` deploys `game/` to GitHub Pages on each push to `main` and can also be run manually from the Actions tab. Repository visibility is managed separately; the workflow does not change it.
