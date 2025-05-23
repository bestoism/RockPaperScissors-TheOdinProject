# 🪨📄✂️ Rock Paper Scissors - Final Project

This is the final project for the **"The Odin Project - freeCodeCamp Remix"** course on freeCodeCamp. It is a simple **Rock Paper Scissors** game where you play against the computer using JavaScript. The interface is minimal and focused on core logic, with interaction handled via browser prompts and results shown in the console.

---

## 📋 Assignment Instructions

Your game will be played against the computer. You will write a function that randomly returns `"rock"`, `"paper"` or `"scissors"`.

You do not need to worry about the front-end part of the game. You will only write the logic for the game. Open the `script.js` and start following the instructions.

### ✅ User Stories

- You should have a function named `getComputerChoice`.
- Your `getComputerChoice` function should return `"rock"`, `"paper"`, or `"scissors"` at random.
- You will write a function named `getHumanChoice` to get the user's input.
- `getHumanChoice` should return a valid choice from the user (case-insensitive).
- You will keep track of the scores using `humanScore` and `computerScore` variables.
- A function named `playRound` will play one round using `humanChoice` and `computerChoice`:
  - If it's a tie, it should return `"It's a tie!"`.
  - If the player wins: `"You win! [player choice] beats [computer choice]"`.
  - If the computer wins: `"You lose! [computer choice] beats [player choice]"`.
- Increment scores accordingly.
- A function named `playGame` will:
  - Play 3 rounds.
  - Call `playRound` in each iteration.
  - Declare the final winner based on who won the most rounds.

---

## ▶️ How to Play

1. Open `index.html` in your browser.
2. Open the browser console (press `F12`, or right-click → `Inspect` → Console tab).
3. Click the "Play Game" button (or reload the page).
4. Follow the prompts in the browser to enter your choice for each round (`rock`, `paper`, or `scissors`).
5. View the round results and score updates in the console.
6. At the end, the console will announce whether you won or lost the game.

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (basic styling with `monospace` font)
- JavaScript (ES6)

---

## 🎯 Features

- Fully functional Rock Paper Scissors game logic.
- Input handled via `prompt()`.
- Round-by-round scoring and result messages.
- Final result displayed after 3 rounds.
- Clean, minimal structure for easy extension (e.g. adding buttons or animations).

---

## 🚀 Future Improvements

- Add buttons and UI instead of prompt-based input.
- Show dynamic score updates on the webpage.
- Allow unlimited rounds or a "best of 5" mode.
- Add sound effects or animations for fun feedback.

---

## 📚 Credits

Built as part of **The Odin Project - freeCodeCamp Remix** course.  
Created by Besto.

---
