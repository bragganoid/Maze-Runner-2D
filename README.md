# Maze Runner 2D

A terminal-based maze game written in Python. Choose a maze file, then guide the player to the exit using the keyboard.

## Features

- Plays maze layouts stored as simple text files
- Displays walls, a player marker, and an exit in the terminal
- Supports continuous movement through corridors until a wall, exit, or branch is reached
- Includes a collection of 25x25 and 65x11 maze layouts

## Requirements

- Python 3

No third-party packages are required.

## Run the game

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

   ```bash
   python "maze runner 2D.py"
   ```

4. At the prompt, enter the path to a maze file, for example:

   ```text
   _all-mazes/maze25x25s1.txt
   ```

   Enter `LIST` to list maze files in the current folder, or `QUIT` to exit.

## Controls

| Key | Action |
| --- | --- |
| `W` | Move up |
| `A` | Move left |
| `S` | Move down |
| `D` | Move right |
| `QUIT` | End the game |

The player keeps moving in the selected direction until reaching a wall, a junction, or the exit.

## Maze file format

Mazes are plain-text grids made from these characters:

| Character | Meaning |
| --- | --- |
| `#` | Wall |
| Space | Open path |
| `S` | Starting position |
| `E` | Exit |

Each maze must include one start (`S`) and one exit (`E`).

## Project structure

```text
.
├── maze runner 2D.py
└── _all-mazes/
    ├── maze25x25s1.txt
    └── maze65x11s1.txt
```

## License

Add a license before publishing if you want to state how others may use, modify, and share this project.
