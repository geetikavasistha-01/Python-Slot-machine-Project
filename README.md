# Python Slot Machine

A simple terminal-based slot machine game built with Python.  
Players can deposit money, choose the number of betting lines, place bets, spin the slot machine, and win based on matching symbols.

---

## Features

- Deposit system
- Configurable betting lines
- Randomized slot machine spins
- Symbol rarity and payout system
- Win detection across selected lines
- Balance tracking throughout the game

---

## How It Works

The slot machine consists of a `3 x 3` grid.

Each symbol has:
- A specific frequency (rarity)
- A payout value

### Symbol Distribution

| Symbol | Count | Value |
|--------|------|------|
| A | 2 | 5x |
| B | 4 | 4x |
| C | 6 | 3x |
| D | 8 | 2x |

- Lower count = rarer symbol
- Higher value = larger payout

You win when all symbols across a selected line match.

---

## Project Structure

slot_machine.py

Main functions:

* `deposit()` → Handles user deposits
* `get_bet()` → Validates betting amount
* `get_number_of_lines()` → Selects betting lines
* `get_slot_machine_spin()` → Generates random slot output
* `check_winnings()` → Calculates winnings
* `spin()` → Runs one game round
* `main()` → Starts and controls the game loop

---

## Installation

Clone the repository:


git clone https://github.com/your-username/python-slot-machine.git


Move into the project directory:

cd python-slot-machine


Run the program:


python slot_machine.py


---

## Example Gameplay


What would you like to deposit? $100

Current balance is $100
Press enter to play (q to quit).

Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10

You are betting $10 on 2 lines. Total bet is equal to: $20

A | B | A
D | D | D
C | B | C

You won $20.
You won on lines: 2


---

## Concepts Used

* Python functions
* Loops and conditionals
* Dictionaries
* Lists
* Input validation
* Random module
* Basic game logic

---

## Future Improvements

* GUI version using Tkinter or Pygame
* Multiple paylines
* Jackpot system
* Save/load balance
* Sound effects and animations
* Adjustable slot dimensions

---

## Requirements

* Python 3.x

No external libraries required.

---

## License

This project is open source and available under the MIT License.

```
```
