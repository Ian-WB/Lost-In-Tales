# Lost in Tales — 3D Puzzle Game (Android)

> A cozy 3D puzzle game set inside classic fairy tales — tap to guide the hero through storybook scenes, pushing blocks sokoban-style, climbing, and setting caged friends free.

**Engine:** Unity 6 (6000.3.15f1) · Universal Render Pipeline  
**Platform:** Android (touch controls)  
**Play it:** [download the APK from Releases](https://github.com/Ian-WB/Lost-In-Tales/releases/latest)  
**Context:** Team project for Axis (Eixo) 2 of the Digital Games program at PUC Minas  
**Original team repository:** [SauloSouza27/Lost-in-Tales](https://github.com/SauloSouza27/Lost-in-Tales)

> **Note on repo history:** this repository is a portfolio snapshot of our academic team project. It preserves the full commit history, so every teammate's authorship is intact. The **My contributions** section below describes my direct work only.

---

## About the game

*Lost in Tales* drops the player into scenes inspired by classic fairy tales — including a certain beanstalk. Across **three levels**, each one a self-contained diorama puzzle, you move your character by tapping the world, push and pull blocks into place, climb ledges, and reach the goal to complete the tale.

- **Tap-to-move** navigation designed for touch screens
- **Sokoban-style block puzzles** — select a block, then push or pull it along the grid
- **Vertical traversal** — climb blocks and scenery to reach higher layers
- **Fairy-tale objectives** — free caged companions, grow the beanstalk, finish the story

---

## Media

<!-- TODO: add gameplay screenshots / a short GIF to docs/media and embed them here:
![Gameplay](docs/media/gameplay-01.png)
Tip: screen-record on an Android device or in the Unity editor with the Simulator view.
-->

*Screenshots coming soon.*

---

## My contributions (Gameplay / Engineering)

The core gameplay mechanics below were built together with Guilherme Oliveira ([@megatruckp](https://github.com/megatruckp)):

- **Tap-to-move player controller** — raycast-based touch input, grid-aligned movement and rotation, with animation hooks
- **Sokoban block mechanics** — block selection, push/pull handling, and interaction rules between movable and pushable pieces
- **Climbing interaction** — contextual climb button and layered (multi-height) movement
- **Cage/objective logic** and camera axis locking

The level design, art, remaining puzzle mechanics (beanstalk, collectible pages, shop), audio, and UI were built by the rest of the team — see [Team](#team).

---

## How to run

**Easiest:** grab the APK from [Releases](https://github.com/Ian-WB/Lost-In-Tales/releases/latest) and install it on an Android device.

To run from source:

1. Clone the repository
2. Open the project with **Unity 6000.3.15f1** (or a newer Unity 6 release) with Android Build Support installed
3. Open `Assets/_Lost in Tales/_Levels/MainMenu.unity`, press Play in the editor (use the Simulator view for touch), or **Build and Run** on an Android device

---

## Team

Academic team project — Digital Games, PUC Minas:

- Saulo Souza — [@SauloSouza27](https://github.com/SauloSouza27)
- Maria Fernanda Silva — [ArtStation](https://www.artstation.com/fernanda828)
- Paulo Antônio — [@Tiofly](https://github.com/Tiofly)
- Guilherme Oliveira — [@megatruckp](https://github.com/megatruckp)
- Lucca Oliveira
- Fabrício Frade — [@FFrade22](https://github.com/FFrade22)
- Ian Barbosa — [@Ian-WB](https://github.com/Ian-WB)

---

## License

Code is licensed under **Apache-2.0** (see [LICENSE](LICENSE)). Art, audio, and design assets belong to their respective authors — please contact the team before reusing them.

## Contact

- GitHub: [Ian-WB](https://github.com/Ian-WB)
