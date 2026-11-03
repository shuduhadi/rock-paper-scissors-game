# ✊ 👋 ✌️ Rock, Paper, Scissors

A command-line Rock, Paper, Scissors game in Python. Play against the computer as many rounds as you like, and see the final score when you quit.

## Features

- Input validation: keeps asking until you enter rock, paper or scissors
- Random computer opponent
- Emoji display of each move
- Running score for you and the computer
- Play-again loop

## Run it

Requires Python 3 (no external packages).

```bash
git clone https://github.com/shuduhadi/rock-paper-scissors-game.git
cd rock-paper-scissors-game
python main.py
```

## Example

```
Welcome to Rock, Paper, Scissors!
Enter rock, paper, or scissors: rock
You chose: ✊
Computer chose: ✌️
You win!

Do you want to play again? (yes/no): no
Thank you for playing!
Your score: 1
Computer score: 0
```

## Project structure

The game is split into small modules, one responsibility each:

| File | Responsibility |
|---|---|
| `main.py` | Game loop, scoring, emoji output |
| `player.py` | Reading and validating the player's move |
| `computer.py` | Picking the computer's move |
| `game_logic.py` | Deciding the winner |
