Console-Based Snake Game

A simple console-based snake game implemented in C++. Play the classic game of controlling a snake to eat food and grow while avoiding collisions with the boundaries and the snake's own body.


Table of Contents

Features
Prerequisites
Getting Started
Controls
Game Rules
Customization
Limitations


Console-based gameplay.
Snake movement controlled by keyboard inputs.
Snake grows in length when it eats food.
Simple collision detection for boundaries and self.
Basic scoring system.
Prerequisites

To play this game, you need:

A C++ compiler that supports standard C++ features.
A terminal or console window to run the game.
Getting Started

Clone the repository to your local machine or download the ZIP file.
Compile the source code using your C++ compiler.
Run the compiled executable in your terminal or console.
Controls

'a': Move the snake left.
'd': Move the snake right.
'w': Move the snake up.
's': Move the snake down.
'x': Exit the game.
Game Rules

The snake starts with a length of one unit.
The snake grows by one unit each time it eats the food.
The game ends if the snake collides with the boundaries or its own body.
Eating the food increases the player's score by 10 points.
The player can exit the game by pressing the 'x' key.
Customization

You can modify the source code to customize the game, add new features, or change the appearance. Some potential customizations include:

Changing the grid size or snake speed.
Adding power-ups or obstacles.
Implementing more advanced collision detection.
Creating a more user-friendly interface.
Limitations

This game uses basic console input/output and might not work on all platforms or terminals.
The code provided is a simple implementation and lacks advanced features found in modern games.
Compatibility with different compilers and environments may vary.


The snake starts in the center of the grid and initially has a length of one unit.
The player can control the snake's movement using the keyboard keys 'a' (left), 'd' (right), 'w' (up), and 's' (down).
The snake's objective is to eat the "food" represented by the character 'F', which appears randomly on the grid.
When the snake eats the food, its length increases, and the player's score increases by 10 points.
The game ends if the snake collides with the boundaries of the grid or with its own body.
The player can exit the game by pressing the 'x' key.
Implementation Details:

The game is implemented using basic C++ features and standard input/output operations.
The grid's dimensions are defined by constants width and height.
The snake's position and direction are tracked using variables x, y, and dir.
The tailX and tailY arrays store the positions of the snake's tail segments.
The nTail variable keeps track of the snake's length.
The fruitX and fruitY variables store the position of the food.
The gameOver variable controls the game loop's termination.
The Setup function initializes the game's variables and positions.
The Draw function renders the game grid, snake, and food on the screen.
The Input function handles keyboard input and updates the snake's direction.
The Logic function updates the game logic, checks for collisions, and handles eating food.
The main game loop repeatedly calls Draw, Input, and Logic, providing the game's real-time behavior.
Note:

This implementation uses basic console output and input for graphics and interaction, which might not be compatible with all systems or terminals.
The implementation provided is simplified and lacks advanced features, smooth movement control, and advanced collision detection.
Users interested in further enhancing the game can explore libraries like ncurses for more advanced console-based graphics and input control.