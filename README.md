


# Assembly End Game

Assembly End Game is a React word-guessing game inspired by Hangman.
The player has a limited number of guesses to reveal a hidden word one letter at a time.
Wrong guesses eliminate programming languages from the list, and the game ends with either a win (word completed) or a loss (guesses exhausted).

![assembly-endgame](https://github.com/user-attachments/assets/3a25ce19-f766-4d15-a8e4-1f60528aec6c)


## Features

- Interactive letter-by-letter guessing
- Real-time game status updates (win/loss/in-progress)
- Visual language elimination feedback for wrong guesses
- Random word selection for replayability
- Keyboard-style on-screen letter controls

## Tech Stack

- React
- JavaScript (ES6+)
- Vite
- CSS

## Project Structure

- `App.jsx` - Main game logic and UI state
- `languages.js` - Data for language labels/colors shown in the game
- `words.js` - Word list used for random game generation
- `utils.js` - Helper utilities for gameplay and rendering
- `index.jsx` - React app entry point
- `index.css` - Styling

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Installation

```bash
npm install
```

### Run in Development

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## How to Play

1. Start a new round.
2. Guess letters using the on-screen keyboard.
3. Correct guesses reveal letter positions in the word.
4. Wrong guesses remove one language.
5. Reveal the full word before running out of guesses to win.

## Future Improvements

- Difficulty levels (easy/medium/hard)
- Score tracking and streaks
- Sound effects and animations
- Better accessibility (keyboard navigation and ARIA enhancements)
