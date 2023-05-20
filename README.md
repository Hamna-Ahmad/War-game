# War Game App

This is a war game app implemented in JavaScript. The game allows you to play a simple card game of war against the computer.

## Features

- New Deck: Click the "New Deck" button to start a new game. It fetches a new shuffled deck of cards from an external API, initializes the game, and enables the draw button.

- Draw Cards: Click the "Draw" button to draw two cards from the deck. The app displays the drawn cards on the interface, updates the remaining cards count, determines the round winner, and updates the scores. It also checks for the end of the game and displays the final result.

## Getting Started

To use the war game app, follow these steps:

1. Clone the repository or download the source code files.
2. Open the `index.html` file in a web browser.
3. Click the "New Deck" button to start a new game.
4. Click the "Draw" button to draw cards and play against the computer.

## Technologies Used

- API
- JavaScript
- HTML
- CSS

## Game Rules

The game follows the rules of the classic card game called "War." Here are the basic rules:

1. A standard deck of 52 playing cards is used.
2. The deck is shuffled, and each player (you and the computer) is dealt one card at a time.
3. The player with the higher card value wins the round.
4. If both players draw cards with the same value, it's a tie.
5. The game continues until all cards have been drawn from the deck.
6. The player with the most won rounds (highest score) at the end of the game wins.

## Code Structure

The main functionality of the game is implemented in the `index.js` file. The code is structured into sections for variable declarations, event listeners, and functions.

The game interface styling is implemented using CSS in the `index.css` file.

## Challenge

The code includes a challenge to modify the asynchronous operations in the `handleClick` and `drawCardBtn` event listener functions to use `async/await` instead of `.then()`.

Feel free to make changes, improve the game, or customize it to suit your needs.

Enjoy playing the war game app!

