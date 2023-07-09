**Snake Game Internship Task Submission Report**

**Introduction:**
This report presents the completion of the Snake Game task as part of the internship application. The Snake Game is a classic video game where the player controls a snake that moves around a grid, eating food and growing longer. The objective is to avoid colliding with the walls or the snake's own body.

**Task Overview:**
The task involved developing a playable version of the Snake Game using a programming language of choice. The game should have the following functionalities:

1. Display a grid-based game board.
2. Control the movement of the snake using keyboard inputs.
3. Generate food at random locations on the game board.
4. Update the snake's position and length as it moves and eats food.
5. Detect collisions with the walls, snake's body, or food.
6. Keep track of the player's score based on the number of food items eaten.
7. Provide a game over condition when the snake collides with a wall or its own body.
8. Implement a restart option to play the game again.

**Implementation Details:**
For this task, I chose to implement the Snake Game using Python programming language and the Pygame library for graphics and user input handling. The following steps were taken to fulfill the task requirements:

1. Setup:
   - Installed Python and Pygame library.
   - Created a new Python script to write the game code.

2. Game Board and Graphics:
   - Created a game window using Pygame's `pygame.display.set_mode()` function.
   - Defined a grid-based game board using a 2D array to represent each cell.
   - Implemented rendering of the game board on the window using Pygame's `pygame.draw.rect()` function.
   - Displayed the snake and food using different colors and shapes.

3. Snake Movement and User Input:
   - Handled keyboard inputs using Pygame's event handling mechanism.
   - Implemented logic to control the snake's movement based on user inputs (arrow keys).
   - Updated the snake's position and length accordingly.

4. Food Generation and Snake Growth:
   - Generated random coordinates for the food item on the game board.
   - Checked for collisions between the snake's head and the food.
   - Increased the snake's length upon food consumption.

5. Collision Detection and Game Over:
   - Checked for collisions with the walls, snake's body, or food items.
   - Implemented game over conditions and displayed a game over message.
   - Provided an option to restart the game upon game over.

6. Scoring:
   - Kept track of the player's score by counting the number of food items eaten.
   - Displayed the score on the game window.

**Conclusion:**
In conclusion, the Snake Game task has been successfully completed. The implemented game features a playable version of the classic Snake Game, allowing the player to control the snake's movement, eat food, grow longer, and avoid collisions. The game provides a scoring system, detects game over conditions, and offers the option to restart the game for continued play.

The development of this Snake Game has not only allowed me to apply my programming skills but also enhance my understanding of game development concepts, user input handling, collision detection, and score tracking. This task has been an exciting and valuable experience, and I am grateful for the opportunity to work on it as part of the internship application.

Thank you for considering my submission. I look forward to any feedback and the opportunity to discuss my implementation further.
