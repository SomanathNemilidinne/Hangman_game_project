# Hangman Game in Python

Welcome to the **Hangman Game**! This fun and interactive game challenges your word-guessing skills. The project is made entirely with Python, and it's a great way to practice your programming skills while having fun!

## 🎮 Overview

In this Hangman game, you will:
- Guess letters to complete a hidden word.
- Keep track of your remaining lives.
- Enjoy artistic representations of your hangman status as you guess!

## 📂 Project Structure

To run the game smoothly, please ensure all files are stored in a single folder. Here’s how the project is structured:

```
/HangmanGame
│
├── hangmanproject.py   # The main game logic.
├── hangman_art.py      # Contains the ASCII art for the game.
└── hangman_words.py    # A list of words for the game.
```

## 📄 Files Description

### 1. `hangmanproject.py`
This file contains the core logic of the Hangman game. It imports necessary modules, chooses a random word, manages user input, and displays the current game state.

### 2. `hangman_art.py`
This file holds the ASCII art used to visualize the hangman stages and the game's logo. Each stage represents the number of lives left.

### 3. `hangman_words.py`
This file is a collection of words that the game can randomly choose from. The more diverse the words, the more fun the game!

## 🛠️ How to Run the Game

1. **Download the Project Files**:
   - Create a folder called `HangmanGame`.
   - Place `hangmanproject.py`, `hangman_art.py`, and `hangman_words.py` inside this folder.

2. **Run the Game**:
   - Open your terminal or command prompt.
   - Navigate to the `HangmanGame` directory.
   - Run the command:
     ```bash
     python hangmanproject.py
     ```

## 🎨 Game Features

- **Word Selection**: A random word from the predefined list.
- **Guess Tracking**: Keep track of correct and incorrect guesses.
- **Lives System**: You start with 6 lives, and each wrong guess costs a life.
- **ASCII Art**: Dynamic display of hangman stages as you guess.

## 📝 Contribution

Feel free to contribute by:
- Adding more words to `hangman_words.py`.
- Enhancing the ASCII art in `hangman_art.py`.
- Improving game logic in `hangmanproject.py`.

---

Happy gaming! If you have any questions or suggestions, feel free to reach out. 🎉
