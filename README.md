# 🎯 Number Guessing Game — C++ Individual Assignment

A console-based number guessing game built in C++ that demonstrates core structural programming concepts including **structs**, **functions**, **arrays**, and **control structures**.

---

## 📌 Project Description

The player tries to guess a randomly generated secret number. After each guess, the game tells them whether the number is higher or lower. The game tracks statistics across multiple rounds and stores a history of guesses per round.

---

## ✨ Features

- **3 Difficulty Levels** — Easy (1–50), Medium (1–100), Hard (1–200)
- **Player Struct** — stores name, total games, total guesses, best score, and history array
- **Guess History** — stores guesses for each round (up to 50 rounds)
- **Statistics Display** — shows average guesses, best score, total games
- **Performance Feedback** — rates the player after each round
- **Main Menu** with Play, Stats, History, and Quit options
- Clean, readable code with comments and consistent formatting

---

## 🧠 Concepts Used

| Concept | Where Used |
|---|---|
| `struct` | `Player` struct, `GameRound` struct |
| Functions | `playRound()`, `updatePlayer()`, `printStats()`, `printHistory()`, etc. |
| Arrays | `player.history[]` — stores guesses per round |
| Control Structures | `while`, `do-while`, `if/else`, `switch` |
| Random Numbers | `rand()` + `srand(time(0))` |
| Pass by Reference | `initPlayer(Player &p)`, `updatePlayer(Player &p, ...)` |

---

## 🚀 How to Run

### Compile
```bash
g++ NumberGuessingGame.cpp -o game
```

### Run
```bash
./game       # Linux / macOS
game.exe     # Windows
```

---

## 📋 Sample Output

```
==========================================
       NUMBER GUESSING GAME (C++)
     Structural Programming Project
==========================================

Enter your name: Moath

Welcome, Moath!

---------- MAIN MENU ----------
1. Play a new round
2. View my statistics
3. View guess history
4. Quit
--------------------------------
Choice: 1

--- Select Difficulty ---
1. Easy   (1 - 50)
2. Medium (1 - 100)
3. Hard   (1 - 200)
Choice: 2

Guess a number between 1 and 100:
Your guess: 50
  >> Too LOW!  Try higher.
Your guess: 75
  >> Too HIGH! Try lower.
Your guess: 63
  >> Correct!

========================================
  The number was: 63
  You guessed it in 3 attempt(s)!
  Excellent! You're a mind reader!
========================================
```

---

## 📁 File Structure

```
/
├── NumberGuessingGame.cpp   # Main source file
└── README.md                # Project documentation
```

---

## 👤 Author

**Moath**  
Structural Programming in C++ — Individual Assignment  
```
