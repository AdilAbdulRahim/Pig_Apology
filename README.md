# Apology Piggy Bank

A small, playful web project I built to turn a simple apology into an interactive experience. Click the piggy bank to add a coin, watch it react, and hear a sound that grows louder as the score increases. Undo and reset controls make it easy to try again.

## What I built

- An interactive piggy bank with animated feedback and coin sounds
- A live score with undo and reset controls
- A responsive layout for desktop and mobile screens
- Local score saving, so progress remains in the same browser

## Tools and techniques

I built the project with **HTML, CSS, and vanilla JavaScript**. I used CSS for the layout, responsive sizing, and interaction effects; JavaScript for click events, score updates, and audio playback; and `localStorage` to save each visitor’s score in their browser. The project includes piggy bank image assets and a coin sound effect.

## What I learned

Building this project gave me hands-on practice connecting interface design to real interactions. I learned how to update the page through the DOM, keep score history for undo, persist state with browser storage, and make a layout adapt across screen sizes. I also worked through small details that shape the experience, like timing visual feedback and handling browsers that block audio until a user interacts.

## Run it

Open `PiggyBank/index.html` in a browser, or host the `PiggyBank` folder as a static website. No account or backend setup is required; each browser keeps its own score.

## Project structure

- `PiggyBank/index.html` — page structure, styles, and game logic
- `PiggyBank/piggy.png` and `PiggyBank/piggy-no-coin.png` — piggy bank artwork
- `PiggyBank/coin.m4a` — coin sound effect
