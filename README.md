# Tic-Tac-Toe

A simple two-player tic-tac-toe game built as a single HTML file with vanilla JavaScript and CSS. No frameworks, no build step — just open and play.

This is my first coding project, built with [Claude Code](https://claude.com/claude-code) as a hands-on way to start learning web development.

## Play it live

**https://praneelganesh-crypto.github.io/tic-tac-toe/**

## How to play

1. Open the live URL above (or open `index.html` locally in any browser).
2. Player **X** goes first. Click any empty square to place your mark.
3. Players alternate turns — the status at the top shows whose turn it is.
4. First player to line up three of their marks in a row, column, or diagonal wins. The winning squares are highlighted in green.
5. If all 9 squares fill up with no winner, it's a draw.
6. Click **New Game** to reset the board and play again.

## Running it locally

Clone the repo and open `index.html` in your browser — no server or install needed.

```
git clone https://github.com/praneelganesh-crypto/tic-tac-toe.git
cd tic-tac-toe
open index.html
```

## What's inside

Everything lives in one file:

- **HTML** — the page structure (title, status line, board container, reset button)
- **CSS** — the dark theme, grid layout, hover effects, and winner highlight
- **JavaScript** — the board state, click handling, and win detection
