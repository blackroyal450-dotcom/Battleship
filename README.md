Battleship
Python Implementation for CSC1011H Final Project
Overview

This project is a Python-based implementation of the classic Battleship game. It was developed as the final practical project for CSC1011H. The game allows a player to place ships, take shots at the enemy board, and play until all ships on one side have been sunk. The design follows object-oriented programming principles and uses a modular structure.

Features

10×10 game board

Automatic ship placement for the computer

Player coordinate input

Validation for overlapping ships and invalid placements

Turn-based gameplay

Hit, miss, and sunk detection

Full game loop until win/lose

Clear console-based display

How to Run

Download or clone the repository:

git clone <repository-link>


Ensure Python 3 is installed.

Run the main game file:

python battleship.py

Project Structure

Adjust filenames if yours differ.

Battleship/
│
├── battleship.py           # Main game controller
├── board.py                # Board class and display logic
├── ship.py                 # Ship class
├── player.py               # Player and Computer logic
├── utils.py                # Optional helper methods
└── README.md               # Documentation

Game Mechanics
Board

A 10×10 grid that tracks ships, hits, and misses.

Player Actions

Players enter coordinates to attack the opponent’s grid. Input is validated to avoid duplicates and out-of-range moves.

Win Condition

The game ends when all ships of one side have been destroyed.

Requirements

Python 3.x

Standard library only

Known Limitations / Future Improvements

Add graphical interface (Tkinter or Pygame).

Add sound or animations.

Add difficulty levels.

Improve AI decision-making.

Author

Mbali Angel Nhlabathi
CSC1011H — 2025
University of Cape Town
