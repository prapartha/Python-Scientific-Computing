# Exercises

## Week 3 – Python Basics (`week3_python_basics.ipynb`)

Introductory Python exercises covering core language features.

### Q1 – Function Practice
A parameterized word-length filter: given a string and integer `n`, return all words of length `n`. Builds on a provided 4-letter-word example using list comprehensions.

### Q2 – Prime Numbers
Implement `primes_up_to(n)` using trial division: iterate from 2 to n, and keep a number if it is not divisible by any previously found prime.

```python
primes_up_to(10)  # → [2, 3, 5, 7]
```

### Q3 – Exception Handling
Write `convert_type(a)` that accepts a string and:
- Returns `int` if the string is a whole number
- Returns `float` if the string contains a decimal point
- Returns the original string otherwise

Uses `try/except` blocks to avoid uncaught `ValueError` exceptions.

### Q4 – Tic-Tac-Toe
Complete a 2-player interactive tic-tac-toe game. Provided helper functions:
- `initialize_board(play)` — resets all 9 squares to empty
- `show_board(play)` — prints the current board state
- `get_move(n, xo, play)` — prompts a player for a valid move
- `check_win(play)` — checks all 8 win conditions (rows, columns, diagonals)

Task: implement `play_game()` to orchestrate the game loop, alternating between players until a winner is found.
