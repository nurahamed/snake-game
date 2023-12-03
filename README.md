### Snake Game
**Snake Game - How to Play**

**Overview:**
Experience classic snake fun with this game. Control the snake using arrow keys or mobile buttons. Collect food to score points. Be cautious; hitting walls or yourself ends the game.

**How to Play:**
- **Keyboard Controls:**
  - **↑** - Move Up
  - **↓** - Move Down
  - **←** - Move Left
  - **→** - Move Right

- **Mobile Controls:**
  - Use the on-screen buttons for direction.

- Click "Play" to start. Enjoy the challenge, and aim for the high score! 🎮
#### Overview

This JavaScript-based Snake Game allows users to play the classic snake game, where the player controls the snake to eat food and grow longer. The game includes features such as sound effects, scoring, and a mobile-friendly interface.

#### Game Constants and Variables

1. **Input Direction:**
   - `inputDir` object stores the current direction of the snake (x and y).

2. **Sounds:**
   - Sound effects (`foodSound`, `gameOverSound`, `moveSound`, `musicSound`) are loaded using the `Audio` constructor.

3. **DOM Elements:**
   - `board` represents the game board.
   - `scoreDisplay` displays the current score.
   - Mobile control buttons (`leftArrow`, `rightArrow`, `upArrow`, `downArrow`, `playGame`) for easier gameplay on mobile devices.

4. **Game Speed and Score:**
   - `speed` determines the speed of the snake.
   - `score` keeps track of the player's score.

5. **Snake and Food Initialization:**
   - `snakeArr` array stores the initial position of the snake.
   - `food` object represents the initial position of the food.

#### Game Functions

6. **Main Game Loop (`main` function):**
   - The main game loop is executed using `requestAnimationFrame`.
   - It checks if enough time has passed to update the game state, and then calls the `gameEngine` function.

7. **Collision Detection (`isCollide` function):**
   - Detects collisions with the snake itself or the game board boundaries.
   - Plays game over sound, resets the game, and updates the high score if a collision is detected.

8. **Game Engine (`gameEngine` function):**
   - Updates the snake's position, checks for collisions, and handles food consumption.
   - Displays the snake and food on the game board.
   - Updates the score and high score.

#### High Score

9. **High Score Logic:**
   - Retrieves the high score from local storage.
   - Updates the high score if the current score surpasses it.

#### User Input Handling

10. **Keyboard Controls:**
    - The game responds to arrow keys for controlling the snake's direction.
    - Plays move sound on each key press.

11. **Mobile Controls:**
    - Mobile-friendly control buttons are provided for left, right, up, down, and starting the game.
    - Buttons toggle their active state when clicked.

12. **Play Again Alert:**
    - Displays an alert to restart the game when a collision is detected.

#### How to Play

1. Open the HTML file in a web browser.
2. Use arrow keys on a computer or click mobile control buttons to navigate.
3. Eat the food to grow the snake and increase the score.
4. Avoid collisions with the snake itself and the game board boundaries.
5. Try to beat your high score!

#### How to Contribute

1. Fork the repository.
2. Create a branch: `git checkout -b feature/new-feature`.
3. Make changes and commit: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Create a pull request.

#### License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize this template according to your specific project details and requirements.
