# Exercises

## Week 5 – Matplotlib Visualization (`week5_matplotlib_exercises.ipynb` / `week5_matplotlib_exercises_alt.ipynb`)

Two completed versions of the same visualization exercise set (done collaboratively in class):

| Problem | Description |
|---|---|
| Q1 – Planetary Orbits | Log-log plot of orbital period vs. distance for the solar system |
| Q2 – Circle Drawing | Parametric circle using `(cos θ, sin θ)` |
| Q3 – Multiple Circles | Generalized `draw_circle(x0, y0, R, color)`; 10 random circles |
| Q4 – Climate Data | NASA GISS temperature anomaly plot: smoothed line + colored scatter (blue/red) |
| Q5 – Subplots | Function, first derivative, and second derivative stacked in a 3-panel figure |
| Q6 – Word Frequency | Parse Star Trek transcript with regex; bar chart of top 25 most frequent words |

---

## Week 5 – Advanced Python (`week5_advanced_python.ipynb`)

| Exercise | Description |
|---|---|
| Rock-Paper-Scissors | Interactive game vs. computer with score tracking |
| Pascal's Triangle | Generate first n rows using `scipy.special.comb` |
| Pangrams | Check if a sentence contains all 26 letters |
| Math Table | Table of angles with sin, cos, and sin²+cos² values |
| Calendar / OOP | `Event` and `Day` classes; weekly schedule with appointments |

---

## SciPy – Numerical Integration (`scipy_numerical_integration.ipynb`)

- Integrates a Gaussian `f(x) = exp(−x²)` using `scipy.integrate.simps`
- Compares numerical result to exact value `√π`
- Error vs. number of sample points — verifies 4th-order (Simpson) convergence

---

## SciPy – Signal Processing (`scipy_signal_processing.ipynb`)

- Adds noise to a synthetic signal
- Applies numerical filtering using Fourier analysis
- Domain: 2048 points over L = 50

---

## SciPy – Linear Algebra (`scipy_linear_algebra.ipynb`)

- Solves linear systems `Ax = b` using Hilbert matrices of increasing size
- Computes condition numbers and solution error to demonstrate numerical instability
- Shows how condition number growth degrades accuracy as matrix size increases

---

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
