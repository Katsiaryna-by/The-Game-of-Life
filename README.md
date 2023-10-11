# Game of Life

The Game of Life is a cellular automaton devised by mathematician John Conway. It operates on a two-dimensional grid where cells can be "alive" or "dead" and evolves based on specific rules.

## Rules of the Game

- Any live cell with fewer than two live neighbors dies.
- Any live cell with two or three live neighbors continues to live.
- Any live cell with more than three live neighbors dies.
- Any dead cell with exactly three live neighbors becomes a live cell.

## How to Play

1. Press the "Create life" button to initiate evolution.
2. Observe the changes in the grid as the game progresses.

## Installation Requirements

In the '[requirements.txt](requirements.txt)' file.

## Running the Application

1. Download the project or clone it from the repository.
2. Open a command prompt and navigate to the project directory.
3. Install the required packages by running the following command: `pip install -r requirements.txt`
4. Start the application with the following command: `python game_of_life.py`
