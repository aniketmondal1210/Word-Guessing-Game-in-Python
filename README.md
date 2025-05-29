# Word Guessing Game

A beginner-friendly word guessing game built using Python. This game demonstrates the use of basic Python concepts such as strings, loops, conditionals, and the `random` module.

## 🎮 Game Description

- The program randomly selects a word from a predefined list.
- The user has 12 chances to guess the word one letter at a time.
- Correct guesses reveal the letter in its correct position.
- Incorrect guesses reduce the number of remaining turns.
- The game ends when the user either guesses the entire word or runs out of turns.

## 🧠 Concepts Used

- `input()` for user interaction
- `random.choice()` to select a word
- `while` loop for the game flow
- String concatenation and conditionals (`if/else`)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/word-guessing-game.git

2. Navigate to the project directory:
   ```bash
   cd word-guessing-game

3. Run the script:
   ```bash
    python word_game.py


📋 Example Output

  What is your name? Gautam
 
  Good Luck! Gautam
  
  Guess the characters
  
  _ _ _ _ _ 
  
  Guess a character: g
  
  g _ _ _ _
  
  Guess a character: e
  
  g e e _ _
  
  ...
  
  You Win
  
  The word is: geeks

  📂 File Structure
  
  word-guessing-game/
  
  ├── word_game.py
  
  └── README.md

  🛠 Requirements

    Python 3.x

  No external libraries are required.
  
  📄 License
  
  This project is licensed under the MIT License.
