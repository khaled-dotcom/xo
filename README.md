# XO (Tic-Tac-Toe) — Console Game

A simple two‑player XO (Tic‑Tac‑Toe) game that runs in the terminal. Players take turns entering a position from 1 to 9 until someone wins or the game ends in a draw.

## Features

- Two players: `X` vs `O`
- Clear 3×3 board display
- Input validation (only `1`–`9`, prevents overwriting moves)
- Win and draw detection

## Requirements

- Python 3.8+

No extra packages are required.

## Run

From the project directory:

```bash
python tic_tak_tok.py
```

## How to play

The board positions are numbered like this:

```
|1|2|3|
|4|5|6|
|7|8|9|
```

When prompted, type the number of the cell you want to place your mark in.

## Project structure

- `tic_tak_tok.py`: game logic and CLI loop

## License

MIT
