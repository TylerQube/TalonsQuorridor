# Talons Qorridor

A Python implementation of an AI designed to play the boardgame Quorridor, which also won a single elimination tournament at the Illinois Math & Science Academy's 2022 Intersession "Teach Your Computer to Play Games".

This repository contains our game-playing AI in /Qorridor/TAlanSPlayer.py, as well as all scaffold code (written by the instructor) required to simulate a game against another player or AI.

Talons uses the A* pathfinding algorithm to determine the shortests path to victory, as well as minimax to examine several moves ahead and select the most advantageous option.

When making a move, Talons compares the move that will reduce its own distance to victory to the move that will most hamper the opponent's progress.

# Intersession2022

Requirements: numpy tqdm pygame

Installing these packages should be as simple as opening command prompt and typing

pip install [package name]

If you know what it is I recommend using a virtual environment but if you don't that's fine this command works anyway. If it doesn't work then ask me about it.

Here's the step-by-step version if you have simple IDLE in Windows:

    Open the Start Menu and type Command Prompt - before you finish it, the program should appear as the Command Prompt desktop app.
    Right-click the Command Prompt program and choose Run as administrator.
    If it asks if it can make changes, select Yes.
    Type:

py -3 -m pip install --upgrade pip

    Then type:

py -3 -m pip install numpy

py -3 -m pip install tqdm

py -3 -m pip install pygame

    Click on the green Code button on the GitHub page
    Choose Download ZIP
    Extract the resulting downloaded file somewhere on your computer.
    Inside the folder, right-click Main.py and choose Edit with IDLE.

