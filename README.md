# ReactJS/TypeScript Hangman Game
- This is a simple Hangman game built with React and TypeScript. Players can guess letters to reveal a hidden word, with the game providing feedback on correct and incorrect guesses.

## Features
- Word Guessing: Players can guess letters from the alphabet.
- UI & Keyboard Input: Input can be made via the on-screen keyboard or the physical keyboard.
- Game Reset: Press the "Enter" key to start a new game with a fresh word.

## Hooks Used
1. **useState**: Manages the state of the game (current word, guesses, game status).
2. **useEffect**: Used for handling side effects like starting a new game when the component mounts.
3. **useCallback**: Optimizes performance by memoizing callback functions.

## How to Run the Game
1. After cloning the reop and installing the node modules using ```bash npm install```
2. To run the dev server use ```bash npm run dev```

## Gameplay Instructions
- Guess a Letter: Click on the letters in the UI or press the corresponding keys on your keyboard.
- New Game: To start a new game with a new word, press the "Enter" key.
- Game Status: The game will display the word with underscores for unguessed letters, and it will indicate how many incorrect guesses you've made.

## Sample Result
<img width="1512" alt="Screenshot 2025-01-28 at 5 45 06 PM" src="https://github.com/user-attachments/assets/4af110a4-f17c-40a2-a0fa-81dd06b8a44b" />
