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


⚙️ How It Works
The secret number is hardcoded as 123.

User enters a guess via input.

Validation checks:

Length of guess must match secret number.

Digits must be unique.

System provides clues based on matching digits and positions:

Fermi for exact matches.

Pico for wrong position matches.

Bagel if no matches at all.

The game continues until the correct guess is made.

💻 How to Run
1. Clone the repository or copy the code into a .py file:

git clone https://github.com/your-username/fermi-bagel-game.git
cd fermi-bagel-game

2. Run the Python script:
python fermi_bagel_game.py

🚀 Features
Simple and interactive terminal-based gameplay.

Input validation (length, duplicates).

Infinite loop until the player wins.

Clear hints that help players learn the game logic.

🧠 Potential Improvements
Randomly generate the secret number instead of hardcoding.

Allow digit length configuration.

Add scoring system and guess counter.

Add difficulty levels.

👨‍💻 Contributors
Ketan Talware

📄 License
This project is licensed under the MIT License.

Feel free to use, modify, and distribute!

📬 Feedback
Found a bug or want to contribute? Feel free to open an issue or pull request!
