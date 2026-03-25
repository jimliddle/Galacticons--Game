# 👾 Retro Galacticons

A fully self-contained, zero-dependency HTML5 arcade game paying homage to the classic space shooters of the 1980s.

Playable entirely in the browser, this game recreates the authentic arcade cabinet experience using modern web technologies—no external images, sound files, or libraries required!

# ✨ Features

- 100% Procedural Pixel Art: All sprites (player, aliens, explosions) are generated dynamically using 2D canvas arrays. No external .png or .gif assets are used.

- Authentic Audio Synthesis: Retro sound effects (laser blasts, explosions, alien dive drones) are generated mathematically on-the-fly using the browser's Web Audio API.

- CRT Shader Simulation: Custom CSS overlays recreate the physical look of a vintage arcade monitor, complete with scanlines, RGB phosphor bleed, screen curvature, and glass glare.

- Progressive Difficulty: The game gets harder as you progress. Aliens dive faster, shoot more often, and start closer to the bottom of the screen.

- Epic Boss Battles: Survive to every 5th level to face off against the giant Alien Boss and its Royal Guards.

Responsive & Mobile-Ready: Playable on desktop and touch devices. Scales to fit your screen while maintaining the classic aspect ratio.

## 🎮 How to Play

The objective is simple: survive the alien onslaught and get the highest score possible.

Desktop Controls

Move: Left / Right Arrow Keys or A / D

Fire: Spacebar

Mobile / Touch Controls

Move: Tap and drag anywhere on the screen to move your ship.

Fire: Auto-fire is engaged automatically as long as you are touching the screen.

Gameplay Tips

You can only have two bullets on the screen at a time. Make your shots count!

You have 3 seconds of invulnerability (blinking) when you respawn. Use it to reposition safely.

Diving enemies are worth double points.

Defeat the Boss (Level 5, 10, etc.) for a massive 1,000-point bonus, but watch out for its 3-way spread attack!

## 🚀 Quick Start

Since the entire game is bundled into a single file, running it is incredibly simple:

Clone or download this repository.

Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge).

Insert Coin (Click or press any key) and play!

## 🛠️ Tech Stack

HTML5 Canvas API: For rendering the starfield, entities, and particles.

Vanilla JavaScript (ES6): For game logic, collision detection, and procedural sprite generation.

Web Audio API: For synthesized sound effects.

CSS3: For the arcade cabinet wrapper, CRT visual effects, and UI overlays.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
