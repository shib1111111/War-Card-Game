# War Card Game

War Card Game is a simple, browser-based implementation of the classic card game *War*. Built with HTML, CSS, and modern JavaScript (ES6 modules), this project simulates a round of War where both the player and the computer flip a card and the higher card wins the round. The game continues until one player's deck is empty, declaring the other as the winner.

## How to Play

- **Start the Game:** Open the `index.html` file in your browser. The game starts automatically.
- **Gameplay:** 
  - Click anywhere on the page to begin a round.
  - Both the player and the computer will flip one card.
  - The higher card wins the round. In case of a draw, each player gets their card back.
- **Game Over:** The game ends when either the player's or the computer's deck is empty. The result will be displayed on the screen.

## Files and Structure

- **index.html**  
  Contains the structure of the game interface, linking to the CSS and JavaScript files.

- **styles.css**  
  Provides the styles and layout for the game interface including deck and card positioning.

- **script.js**  
  Implements the main game logic:
  - Handling game rounds and user interactions.
  - Flipping cards and updating the deck counts.
  - Checking for round winners and determining the game outcome.

- **deck.js**  
  Defines the `Deck` and `Card` classes:
  - **Deck Class:** Manages the collection of cards, shuffling, and card distribution.
  - **Card Class:** Creates individual cards with suit, value, and visual representation (using HTML elements).

## Features

- **Simple and Interactive Gameplay:** Easily play rounds by clicking anywhere on the screen.
- **Dynamic Card Rendering:** Cards are dynamically generated and displayed using DOM manipulation.
- **Modular Codebase:** Uses ES6 modules for a clean and maintainable code structure.
- **Responsive Design:** The interface adapts to different screen sizes and devices.

## Getting Started

To run the game locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/war-card-game.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd war-card-game
   ```
3. **Open `index.html` in your Browser:**
   - You can simply double-click the file, or use a local development server for a better experience.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit an issue or open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

<em style="color: #ff66b2; font-weight: bold;">✨ --- Designed & made by Shib Kumar Saraf ✨</em>
