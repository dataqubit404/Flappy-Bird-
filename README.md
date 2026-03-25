# 🐦 Flappy Bird — Neon Sky Edition

A modern, high-performance Flappy Bird clone built with **HTML5 Canvas**, **CSS3**, and **Vanilla JavaScript**. This version features a sleek "Neon Sky" aesthetic, dynamic difficulty scaling, and a particle physics system.

🚀 Live Demo : https://flappy-bird-three-phi.vercel.app/

## ✨ Features

* **Dynamic Difficulty:** The game gets progressively harder (tighter gaps and faster speeds) as your score increases.
* **Neon Aesthetics:** A beautiful night-sky background with glowing stars, parallax clouds, and neon-styled pipes.
* **Smooth Physics:** Custom gravity and rotation physics for a responsive "weighty" feel.
* **Particle System:** Visual feedback through "flap" particles and explosive score celebrations.
* **Web Audio API:** Procedurally generated sound effects for jumping, scoring, and collisions (no external MP3 files required).
* **Responsive Design:** Automatically scales to fit mobile, tablet, and desktop screens.
* **Local High Score:** Saves your personal best score using the browser's `localStorage`.

## 🎮 How to Play

### Controls
* **Spacebar / Up Arrow:** Flap/Jump.
* **Mouse Click / Touch Tap:** Flap/Jump.
* **P Key:** Toggle Pause.
* **ESC Key:** Resume from Pause.

### Objective
Navigate the bird through the gaps in the pipes. Each successful pass earns you **1 point**. The game ends if you collide with a pipe or hit the ground.

## 🛠️ Technology Stack

* **HTML5 Canvas:** For high-frame-rate game rendering.
* **CSS3 Variable & Animations:** For UI overlays and neon glowing effects.
* **JavaScript (ES6+):** Clean, modular code managing game state and physics.
* **Google Fonts:** Utilizing 'Fredoka One' and 'Nunito' for a playful, polished UI.

## 🚀 Quick Start

Since this project is built with Vanilla JS, you don't need to install any dependencies.

1.  **Download** the three files: `index.html`, `style.css`, and `script.js`.
2.  Place them in the **same folder**.
3.  **Open** `index.html` in any modern web browser (Chrome, Firefox, Safari, or Edge).

## 📂 File Structure

```text
.
├── index.html   # Main structure and UI overlays
├── style.css    # Game styling and neon effects
└── script.js    # Game engine, physics, and logic