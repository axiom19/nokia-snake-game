# nokia-snake-game
Nokia's Snake game with boundary locked level as a python programming game

A classic snake game built with Python and Turtle graphics.

The player controls a snake which grows longer as it eats food pellets on the screen. The goal is to grow the snake as long as possible without colliding with the walls or the snake's own body.

Features
Smooth snake movement using Turtle graphics
Snake increases in speed as it gets longer
Randomly spawning food pellets
Collisions with walls and self result in game over
Score tracking based on food eaten
Code Structure
The game uses a simple object oriented structure with the following classes:

Snake - Handles snake movement and growth logic
Food - Spawns and manages food pellet pickup
Scoreboard - Tracks and displays score
Game - Manages game loop, interactions, and gameover logic
The main.py file initializes the game objects, sets up the screen, controls the game loop, and contains the game over sequence.

Installation
The game requires Python 3 and the Turtle graphics module. Clone the repo and run python main.py to launch.

Next Steps
Some possible extensions:

Add snake collision sound effects
Let player choose snake speed
High score saving
Multiple levels
Powerups
Obstacles
This provides a simple but fun and addictive game using Python's built-in graphics.
