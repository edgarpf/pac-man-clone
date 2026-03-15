# 🕹️ Arcade Pac-Man Clone

A fully playable, retro-style Pac-Man clone built entirely in a **single HTML file** using HTML5 Canvas, CSS3, and Vanilla JavaScript. No external libraries, no image assets, and no audio files required!

👉 **[PLAY THE GAME LIVE HERE](https://edgarpf.github.io/pac-man-clone/)** 👈

## ✨ Features

* **Zero Dependencies:** The entire game logic, styling, and audio generation live inside one `pacman.html` file.
* **📱 Mobile-Friendly:** Fully responsive arcade cabinet design that scales to fit any device, complete with swipe and tap touch controls.
* **Infinite Levels & Dynamic Difficulty:** The game progresses infinitely. Every time you clear a stage, the level increases, and an additional ghost spawns to ramp up the difficulty.
* **Procedural Spawning:** Ghosts are spawned dynamically in random, valid map locations—safely away from Pac-Man's starting point.
* **Web Audio API Synthesizer:** Classic arcade sounds (the "waka-waka" movement, level clear jingle, and death sound) are generated entirely via code using browser oscillators.
* **Retro Aesthetic:** Features a classic 8-bit font, neon colors, and a CSS-based CRT scanline overlay to simulate playing on an old arcade cabinet.
* **Smooth Animation:** Grid-based movement with dynamic mouth animation that adapts to Pac-Man's movement state and direction.

## 🎮 How to Play

1.  **Start/Restart:** Press the `SPACEBAR` or `TAP` the screen to insert a coin and start the game.
2.  **Movement:** Use the `ARROW KEYS` (Up, Down, Left, Right) or `SWIPE` on your screen to navigate the maze.
3.  **Objective:** Eat all the yellow dots on the screen to advance to the next level.
4.  **Avoid Ghosts:** If a ghost catches you, it's Game Over! 

## 🚀 How to Run Locally

Because this project is completely self-contained, there is no installation or build process required to run it on your machine.

1. Clone or download this repository.
2. Double-click the `pacman.html` file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Press `SPACEBAR` or tap the screen and enjoy!

## 🛠️ Technologies Used

* **HTML5 Canvas:** For rendering the map, Pac-Man, and the ghosts.
* **Vanilla JavaScript (ES6+):** For the game loop, physics, collision detection, procedural generation, and touch events.
* **CSS3:** For the arcade cabinet styling, glowing neon effects, responsive design, and CRT scanlines.
* **Web Audio API:** For synthesizing 8-bit sound effects natively in the browser.

## 🗺️ Roadmap / Future Improvements

* [ ] Add "Power Pellets" in the corners to turn ghosts blue and make them edible.
* [ ] Implement a local storage High Score system.
* [ ] Add different ghost AI behaviors (e.g., chasing, ambushing, wandering).

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to fork, modify, and learn from the code!
