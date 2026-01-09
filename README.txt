❌ Tic Tac Toe / Piškvorky ⭕
A clean, console-based implementation of the classic Tic Tac Toe game. This project focuses on logic implementation, input validation, and user-friendly console visualization using Python.

🇬🇧 English Version
🎯 Project Overview
This project is a classic Tic Tac Toe game implemented in Python. Two players take turns entering numbers from 1 to 9 to place their symbols (X or O) into a 3×3 grid. The game features automatic win/draw detection and a color-coded console interface.

✨ Key Features
Turn-based Gameplay: Smooth transition between Player X and Player O.

Input Validation: Handles incorrect inputs to ensure a seamless experience.

Win Logic: Automatic check for rows, columns, and diagonals.

Enhanced Visuals: Uses colorama for a better terminal UI experience.

Type Hinting: Codebase uses typing for better readability and maintainability.

🛠️ Tech Stack
Language: Python 3.12+

Libraries: * colorama (Terminal text styling)

typing (Static type hinting)

🚀 Installation & Run
Clone the repository:

Bash

git clone <repository-url>
cd tic_tac_toe
Install dependencies:

Bash

pip install -r requirements.txt
Start the game:

Bash

python main.py
🇨🇿 Česká verze
📌 Popis projektu
Klasická hra piškvorky implementovaná v Pythonu. Dva hráči se střídají v zadávání pozic (1–9), čímž vkládají své symboly do mřížky 3×3. Hra automaticky vyhodnocuje vítězství nebo remízu a nabízí přehledné barevné zobrazení v konzoli.

✨ Funkcionality
Střídání hráčů: Logika pro plynulé tahy hráčů X a O.

Validace vstupů: Ošetření chybných zadání od uživatele.

Detekce konce: Automatická kontrola vítězných kombinací a remízy.

Barevné rozhraní: Využití knihovny colorama pro lepší orientaci v terminálu.

📊 Ukázka hry / Example Gameplay
Plaintext

Player X, choose position (1-9): 5
   |   |
---+---+---
   | X |
---+---+---
   |   |
💡 Tip pro sekci "About" na GitHubu:
Do popisku repozitáře vlož:

Simple yet robust Tic Tac Toe implementation in Python featuring colorized terminal output and strict type hinting. Developed as part of the Engeto Data Analyst course.

🐍 Příklad komentovaného kódu (v angličtině):
Pokud ve hře kontroluješ vítěze, tvůj kód s anglickými komentáři by mohl vypadat takto:

Python

from typing import List

def check_winner(board: List[str]) -> bool:
    # Define all possible winning combinations (rows, columns, diagonals)
    win_combinations = [
        (0, 1, 2), (3, 4, 5), (6, 7, 8), # Rows
        (0, 3, 6), (1, 4, 7), (2, 5, 8), # Columns
        (0, 4, 8), (2, 4, 6)             # Diagonals
    ]
    
    for combo in win_combinations:
        # Check if all three positions in a combination are the same and not empty
        if board[combo[0]] == board[combo[1]] == board[combo[2]] != " ":
            return True
    return False
👤 Autor / Author: Adam Seifert

Kontakt: seifert.promotion@gmail.com

Projekt vznikl v rámci kurzu Datový Analytik s Pythonem od Engeto.
