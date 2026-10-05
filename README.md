# Battleship

A browser-based Battleship game built as part of [The Odin Project](https://www.theodinproject.com/).

## 🔗 Links

* [Live Preview](https://jdy7149.github.io/Battleship/)
* [GitHub Repository](https://github.com/jdy7149/odin-batttleship)

## 🛠️ Tech Stack

* JavaScript
* HTML
* CSS
* Jest
* Webpack

## 📌 Overview

This project is a browser-based implementation of the classic Battleship game.

The project focuses on organizing the game logic into separate modules and objects rather than placing all functionality in the DOM layer. The game includes a 10×10 board, ship placement, attacks, and turn-based gameplay.

## ✨ Features

* 10×10 game board
* Ship placement and positioning
* Player and computer gameplay
* Attack and hit/miss handling
* Game state management through `GameController`
* Randomized computer ship placement and attacks
* Game-over detection
* Unit tests with Jest

## 🧩 Project Structure

The game logic is separated into different responsibilities:

* **Ship** — manages ship state, including hits and sinking
* **Gameboard** — manages the board, ship placement, and attacks
* **Player** — represents the player and their actions
* **GameController** — manages the overall game flow and state
* **DOM/UI** — handles rendering and user interaction

This structure helped keep the game logic independent from the DOM and made individual components easier to test.

## 🧪 Testing

Jest was used to test the core game logic, including:

* Ship hit and sunk states
* Ship placement
* Attack results
* Gameboard behavior
* Player actions

Testing the core logic separately from the UI made it easier to verify that changes did not break existing behavior.

## 📚 What I Learned

Through this project, I learned how to:

* Break a larger problem into smaller modules with clear responsibilities
* Manage game state without tightly coupling it to the DOM
* Use JavaScript objects and modules to organize application logic
* Write unit tests with Jest
* Connect application logic with DOM events and rendering
* Use Webpack to bundle a JavaScript application

## 💡 Reflection

One of the main challenges was deciding where each piece of game logic should belong. Rather than handling everything directly in the UI, I separated responsibilities between the game objects and the controller.

This made the code easier to reason about and allowed the core game logic to be tested independently of the browser UI.
