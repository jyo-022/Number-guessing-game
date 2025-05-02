 🎯 Number Guessing Game
This is a simple Python-based **Number Guessing Game**, developed as part of the **Basic Level Projects - Task 2** during my internship at **Codveda Technology**.

📝 Description
The game randomly generates a number between 1 and 100. The player is given up to 10 chances to guess the correct number. After each guess, the program provides feedback indicating whether the guess was too high or too low. The game ends when the user either guesses the number correctly or exhausts all attempts.

💡 Objectives
- Utilize the `random` module to generate a number.
- Accept and validate user input.
- Provide real-time feedback after each guess.
- Handle both correct guesses and failed attempts gracefully.

 🚀 How It Works
1. A random number between 1 and 100 is selected using `random.randint(1, 100)`.
2. The user has 10 attempts to guess the number.
3. Feedback is provided:
   - 🔼 "Too high!" if the guess is more than the secret number.
   - 🔽 "Too low!" if the guess is less than the secret number.
4. The game ends with either a congratulations message or reveals the correct number after all attempts.

 🖥️ Run the Game
python number_guessing_game.py
