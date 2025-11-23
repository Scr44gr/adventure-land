# Adventure Land

> Hello, me from the future (and anyone else who comes here). This is an experiment. I want to see how far Python alone can go when it comes to game development. I chose Adventure Land because I think it's a great project. To be honest, I don't know how far I'll get or if I'll end up with something playable.


So, basically, this is a Python reimplementation of [Adventure Land](https://adventure.land/), an online multiplayer RPG game originally built with Arepy. My goal is to recreate the core mechanics and gameplay using Python, exploring its capabilities in game development.

Arepy is kind of a framework/game engine for building games with Python, made by me. You can check it out [here](https://github.com/Scr44gr/arepy).


# Project Architecture

The project is structured as follows:

- `adventure_land/`: This directory contains the main game code.
  - `__init__.py`: Initializes the package and defines the version.
  - `game/`: This subdirectory will contain the core game logic and mechanics.
  - `servers/`: This subdirectory will handle server-side logic and networking.
  - `client/`: This subdirectory will manage client-side interactions and user interface.
  - Other modules and packages will be added here as development progresses.
- `assets/`: This directory will store game assets such as images, sounds, and other media.
- `tests/`: This directory will contain unit tests for the game.