

# 🛡️ The C Arsenal: Games & Utilities

### 👤 **Created by: Nalinakshan (Code Knight)**

* *Student & Embedded Systems Enthusiast*
* *Exploring the logic behind the machine.*

---

## 📜 Repository Overview

Welcome to my collection of C programming projects. This repository contains **four distinct applications** designed to explore fundamental programming concepts, algorithm design, and user interaction.

**Projects included in this repository:**

1. **Tic-Tac-Toe (XO Game):** An interactive Player vs. Computer strategy game.
2. **Number Guessing Game:** A loop-based logic game with "High/Low" feedback.
3. **Temperature Converter:** A precision tool for Celsius/Fahrenheit conversion.
4. **Arithmetic Calculator:** A switch-case based mathematical utility.

---

## 🌟 Featured Project: Command-Line Tic-Tac-Toe (XO)

This is the flagship project of the repository—a fully functional, console-based implementation of the classic board game.

### 🎮 How It Works

* **Opponent:** You play as **'X'** against the Computer's **'O'**.
* **The Engine:** The game utilizes a robust checking algorithm to detect wins (rows, columns, diagonals) or ties after every move.
* **Smart Play:** The computer automatically reacts to your moves using randomized logic for replayability.
* **Loop:** Includes a replay feature so you can play multiple rounds without restarting the program.

```c
// Sample Logic Snippet
if (winner == PLAYER) {
    printf("You Win!");
} else if (winner == COMPUTER) {
    printf("You Lose!");
}

```

---

## 📂 Utility Projects

### 2. 🎲 Number Guessing Game

A logic-building exercise focusing on loops and conditionals.

* **Core Concept:** Uses `srand(time(0))` to generate a truly random number between 1 and 100 every session.
* **Mechanics:** The program guides the user with "Too High" or "Too Low" hints until the correct number is found.
* **Score:** Tracks the total number of guesses taken.

### 3. 🌡️ Temperature Converter

A scientific utility for unit conversion.

* **Core Concept:** Mathematical formula implementation and character handling.
* **Features:**
* Converts **Celsius to Fahrenheit** ().
* Converts **Fahrenheit to Celsius** ().
* Includes case-insensitive input (accepts 'c' or 'C').



### 4. 🧮 Simple Calculator

A fundamental tool demonstrating control flow.

* **Core Concept:** Utilizes the `switch` statement for efficient operation selection.
* **Operations:** Supports Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
* **Precision:** Uses `double` data types to handle decimal calculations accurately.

---

## 🛠️ Build & Run Instructions

To run these projects, you need a C compiler (like GCC). I recommend saving each code block into its own file (e.g., `game.c`, `calc.c`).

**1. Clone the Repository:**

```bash
git clone https://github.com/YourUsername/C-Arsenal.git

```

**2. Compile (Example for Tic-Tac-Toe):**

```bash
gcc tictactoe.c -o game

```

**3. Run:**

```bash
./game   # On Linux/Mac
game.exe # On Windows

```

---

## 🧩 Concepts Mastered

* **Arrays:** 2D arrays used for the Tic-Tac-Toe grid.
* **Pointers & Memory:** Efficient data handling.
* **Control Flow:** Complex `if-else`, `switch`, and `do-while` loops.
* **Standard Libraries:** `<stdio.h>`, `<stdlib.h>`, `<time.h>`, `<ctype.h>`.

---

> "Code is the language of logic." – Code Knight

*Last Updated: 2026*
