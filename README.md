# TGGB Guido-Bambino

**The Greco Guido Bambino**

A lightweight, local-first browser arcade game where Guido-Bambino hops
across a floating isometric cube arena, changes cube colors, dodges Rival
Guidos, and can even wear your face.

TGGB is built as a **Single-File Local Application (SFLA)**. The game
runs directly in a modern browser with no application server, package
manager, framework, installation process, or third-party runtime
dependencies.

Load your own local image, crop the face you want to use, and become
Guido-Bambino while you clear the arena one cube at a time.

> **Forget about it...**

![TGGB Guido-Bambino screenshot](screenshot.jpeg)

## Play TGGB

**[▶ Play TGGB Guido-Bambino in your browser](https://mikejamesgreco.github.io/tggb-guido-bambino/)**

No installation is required. The GitHub Pages version runs TGGB directly
in your browser, just like opening the standalone `tggb-guido-bambino.html`
file locally.

------------------------------------------------------------------------

## Features

- Isometric cube-hopping arcade gameplay
- Floating circular/hexagonal arena of cubes
- Change every cube top to complete a level
- Randomized Rival Guido characters with their own looks and gold chains
- Rival encounters with an audible "Forget about it!" callout
- Occasional wiseguy sedan drive-by asking, "Did anyone order a pizza?"
- Increasing levels and difficulty
- Score, lives, level, and local high score tracking
- Intuitive Q/E/A/D and arrow-key movement, with touch controls
- Optional local face image for the Guido-Bambino character
- Interactive crop and zoom tool for positioning your face
- Cartoon default Guido-Bambino with pompadour, muscle shirt, tiny shoes, and gold chains
- Retro arcade presentation with stars, skyline, and colorful cube graphics
- Single-file HTML application
- No frameworks or third-party runtime dependencies

------------------------------------------------------------------------

## Getting Started

You can either use the **[hosted TGGB game](https://mikejamesgreco.github.io/tggb-guido-bambino/)**
or download/clone the repository and open:

```text
tggb-guido-bambino.html
```

in a modern web browser.

Use the movement controls to hop diagonally from cube to cube. Landing
on a cube changes its top color. Change every cube to complete the level
while avoiding Rival Guidos and staying on the floating arena.

Choose **Load Face** if you want to replace the default Guido-Bambino
face with an image from your computer. Use the crop and zoom controls to
position the face before playing.

No installation, web server, or build process is required.

------------------------------------------------------------------------

## Controls

TGGB supports both keyboard and touch controls.

```text
Q / Left Arrow    Up-left
E / Up Arrow      Up-right
A / Down Arrow    Down-left
D / Right Arrow   Down-right

Z                 Down-left (alternate)
C                 Down-right (alternate)
```

Touch controls are also available directly in the game interface.

------------------------------------------------------------------------

## Local-First

TGGB is designed to keep the game simple and your images local.

Images selected in TGGB are processed in your browser and are not
uploaded to a TGGB server. They are used for the game session and remain
under your control.

TGGB follows the same **Single-File Local Application (SFLA)**
philosophy as the other Greco browser applications: use browser-native
capabilities where practical and avoid unnecessary runtime
infrastructure.

------------------------------------------------------------------------

## Repository Structure

The repository can remain very simple:

```text
tggb-guido-bambino/
│
├── index.html                    # GitHub Pages launcher
├── tggb-guido-bambino.html      # Standalone TGGB game
├── screenshot.jpeg              # Project screenshot
├── README.md
└── LICENSE
```

------------------------------------------------------------------------

## Browser Support

TGGB is designed for modern desktop browsers and also supports touch
controls on compatible devices. Exact browser behavior can vary slightly
for speech, audio, and local file handling.

------------------------------------------------------------------------

## Privacy

Your selected face image remains local to your browser and is used only
by the game. TGGB does not require an account, backend service, or image
upload.

------------------------------------------------------------------------

## License

See the repository `LICENSE` file for details.

------------------------------------------------------------------------

## Author

**Michael J. Greco**

TGGB Guido-Bambino — **The Greco Guido Bambino**

© mikejamesgreco.me LLC. All rights reserved.
