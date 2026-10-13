# Hangman v1

## Project Overview

This project is a simple, single-player **Hangman** game that runs in the terminal.

The goal of the game is for the player to guess a secret word chosen by the computer, one letter at a time. The player can miss a maximum of **6 times** before losing.

The application should be simple, easy to understand, and easy to use.

## How the Game Works

1. When a new game begins, the computer picks a random word from a word list.
2. The player sees the word as blanks (for example `_ _ _ _ _ _`).
3. The player guesses **one letter** at a time.
4. After each guess, the player should be told whether the letter was:
   - In the word (the letter is revealed in every position it appears)
   - Not in the word (the hangman gets another body part)
   - Already guessed (no penalty)
5. The player should always be able to see how many guesses they have remaining, plus the wrong letters they have already tried.
6. The player may miss a maximum of **6 times**.

## Winning and Losing

The player **wins** if they reveal every letter of the word before running out of guesses.

The player **loses** if they miss 6 times before completing the word.

When the game ends:

- Display a message box telling the player whether they won or lost.
- If the player lost, let them know what the word was.
- When the player presses Enter to close the message, automatically start a new game.

## Project Guidelines

When working on this project:

- Keep the application simple and beginner-friendly.
- Do not add features that were not requested.
- Keep the game focused on a single player.
- Make instructions and messages clear to someone using the game for the first time.
- Before making major changes to how the game works, explain the proposed change first.
- Use the project resources and instructions provided in this repository as guidance.
