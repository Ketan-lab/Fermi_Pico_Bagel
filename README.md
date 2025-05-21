# 🎯 Fermi and Bagel Number Guessing Game

A simple Python console game inspired by classic deduction games like Mastermind. The player guesses a secret 3-digit number with no repeating digits, and the system provides clues to help deduce the correct number.

---

## 🎮 How to Play

- The computer chooses a secret 3-digit number (e.g., `123`).
- You must guess the number with **unique digits** (e.g., `321`).
- After each guess, you receive one of the following clues:
  - **Fermi**: A digit is correct and in the correct position.
  - **Pico**: A digit is correct but in the wrong position.
  - **Bagel**: No digits are correct.
- Guess correctly to win the game!

---

## 🔁 Example Game Output

```bash
Enter your guess: 321
PicoFarmiPico

Enter your guess: 123
Fermi Fermi Fermi 
You Win
