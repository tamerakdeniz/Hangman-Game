# 🎮 Hangman Game

A classic word guessing game implemented in Python where players try to guess a word one letter at a time.

## ✨ Features

- Random word selection from a predefined word list
- ASCII art display of the hangman
- Lives system with visual feedback
- Input validation and duplicate guess detection
- Clear game progress display

## 🎯 How to Play

1. Run the game by executing `main.py`
2. A random word will be selected and displayed as underscores
3. Guess one letter at a time
4. You have 6 lives - each wrong guess loses a life
5. Win by guessing the word before running out of lives
6. Lose if the hangman is completed (0 lives remaining)

## 📋 Game Rules

- Each underscore represents a letter in the word
- Correct guesses reveal the letter's position(s)
- Incorrect guesses reduce remaining lives
- Repeated guesses are not penalized
- Game ends when the word is guessed or lives run out

## 📁 Files

- `main.py` - Main game logic
- `hangman_words.py` - Word list
- `hangman_art.py` - ASCII art for game display
