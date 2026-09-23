# Roll & Hold

Roll & Hold is a two-player dice game built with HTML, CSS, and vanilla JavaScript. Players take turns rolling the dice, accumulating points, and choosing when to hold their score. The first player to reach the winning score wins the game.

## Features

* Two-player turn-based gameplay
* Random dice rolling
* Current score tracking
* Total score tracking
* Hold functionality
* Automatic player switching
* Winning state detection
* New game functionality
* Interactive game interface
* Responsive design

## Project Structure

```text
Roll-and-Hold/
├── index.html      # Main game structure
├── style.css       # Game styling
├── script.js       # Game logic and interactions
└── dice-*.png      # Dice images
```

## Run Locally

Install [Node.js](https://nodejs.org/) and `live-server` globally before running the project:

```bash
npm install -g live-server
```

Clone the repository, enter the project directory, and start the local server:

```bash
git clone https://github.com/athumanrajab/Roll-and-Hold.git
cd Roll-and-Hold
live-server
```

Then open:

```text
http://127.0.0.1:8080
```

## How to Play

1. Player 1 starts the game.
2. Click **Roll Dice** to roll the die.
3. The rolled number is added to the current score.
4. If a **1** is rolled, the current score is lost and the turn switches.
5. Click **Hold** to add the current score to the player's total score.
6. The turn then switches to the other player.
7. The first player to reach the winning score wins.
8. Click **New Game** to restart.

## Technologies

* HTML5
* CSS3
* Vanilla JavaScript
* DOM Manipulation
* JavaScript Events

## Visit the Website

```text
https://athumanrajab.github.io/Roll-and-Hold/
```

## Contact

Email: [athumanrajab0903@gmail.com](mailto:athumanrajab0903@gmail.com)

Phone: +255 795 077 000
