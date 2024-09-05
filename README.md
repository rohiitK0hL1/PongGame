# Pong Game

This is a Python implementation of the classic Pong game, with added features like hand detection for player interaction. The game is designed using object-oriented principles and utilizes several utility modules for various game functionalities.

## Project Structure

- *main.py*: The entry point for the game. It handles the initialization and execution of the game loop.
- *utils/*: Contains utility modules that handle various game components such as paddles, ball, collisions, constants, and hand detection.
  - *Ball.py*: Defines the Ball class and handles ball movement and behavior.
  - *Paddle.py*: Defines the Paddle class, managing player-controlled paddles.
  - *collision.py*: Manages collision detection between the ball and paddles or boundaries.
  - *constants.py*: Contains constant values used throughout the game (e.g., screen size, speed).
  - *hand_detection.py*: Implements hand-tracking functionality for paddle control using external libraries (e.g., OpenCV).

## Features

- *Classic Pong Mechanics*: Traditional gameplay where players use paddles to hit a ball back and forth.
- *Hand Detection*: Control the paddle using hand gestures (when using the appropriate hardware and libraries).
- *Collision Detection*: Precise collision management to ensure smooth gameplay between the paddles and the ball.

## Requirements

Before running the game, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
