# Flappy Bird Game

This project is a game developed using Python, Pygame library.

## Description

Flappy Bird is a desktop game inspired by the classic flappy bird game. The player controls a bird, attempting to fly between columns of green pipes without hitting them.

## Installation

- Make sure Python 3.x is installed on your machine.
- Install the required packages from requirements.txt file: `pip install -r requirements.txt`
  

## How to Run

- Use the command `python3 <filename.py>` to execute the game. Replace `<filename.py>` with the name of the file containing the code.

## Project Structure

- `cfg.py:` Contains the configuration files like screen width, height and paths to various images and audio files.
- `modules.py:` Contains components for the game like bird, pipes etc.
- `main function:` Contains the game loop where all the magic happens. Each iteration in the loop represents a frame in the game. It blits images, checks for collision and updates the score.

## Gameplay

- The player can make the bird 'flap' and move upwards by pressing 'SPACE' or 'UP' key.
- The player has to navigate the bird such that it doesn't collide with the pipes.
- The score increments as the player successfully navigates through the pipes.

Enjoy the game!