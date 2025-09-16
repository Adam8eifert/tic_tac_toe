Perfektní, takže to ještě upravíme: přidáme zmínku o **`requirements.txt`** (s balíčky `typing`, `colorama`) a do sekce Autor dopíšeme, že projekt vznikl v rámci kurzu Engeto.

---

# 📄 README.md (upravená verze)

````markdown
# Tic Tac Toe / Piškvorky

## 📌 Popis projektu (CZ)

Tento projekt je klasická hra **piškvorky (tic-tac-toe)** implementovaná v jazyce **Python**.  
Dva hráči se střídají v zadávání čísel od **1 do 9**, čímž vkládají své symboly (**X** nebo **O**) do hrací mřížky 3×3.  
Hra končí vítězstvím jednoho z hráčů, nebo remízou, pokud je mřížka zaplněná.

### ✨ Funkcionality
- Dva hráči se střídají v tazích  
- Zadávání pozice pomocí čísel 1–9  
- Automatická kontrola vítězství (řádky, sloupce, diagonály)  
- Detekce remízy při zaplněné mřížce  
- Přehledné zobrazení aktuální hrací desky v konzoli  

### 🛠️ Technologie
- Python 3.x  
- Použité balíčky:  
  - `typing`  
  - `colorama`  

### 📦 Instalace
1. Naklonujte repozitář:
   ```bash
   git clone <url-repozitáře>
   cd tic_tac_toe
````

2. Nainstalujte závislosti:

   ```bash
   pip install -r requirements.txt
   ```
3. Spusťte hru:

   ```bash
   python main.py
   ```

### 📊 Ukázkový průběh hry

```
Hráč X, vyber pozici (1-9): 5
   |   |
---+---+---
   | X |
---+---+---
   |   |

Hráč O, vyber pozici (1-9): 1
 O |   |
---+---+---
   | X |
---+---+---
   |   |

...
Výsledek: Hráč X vyhrává!
```

---

## 📌 Project Description (EN)

This project is a classic **Tic Tac Toe** game implemented in **Python**.
Two players take turns entering numbers from **1 to 9** to place their symbols (**X** or **O**) into a 3×3 grid.
The game ends with either a winner or a draw if the grid is full.

### ✨ Features

* Two-player turn-based gameplay
* Position input via numbers 1–9
* Automatic victory detection (rows, columns, diagonals)
* Draw detection when the grid is full
* Clear console-based visualization of the game board

### 🛠️ Technologies

* Python 3.x
* Used packages:

  * `typing`
  * `colorama`

### 📦 Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd tic_tac_toe
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Start the game:

   ```bash
   python main.py
   ```

### 📊 Example gameplay

```
Player X, choose position (1-9): 5
   |   |
---+---+---
   | X |
---+---+---
   |   |

Player O, choose position (1-9): 1
 O |   |
---+---+---
   | X |
---+---+---
   |   |

...
Result: Player X wins!
```

---

## 👤 Autor / Author

* Jméno / Name: Adam Seifert
* Kontakt / Contact: [seifert.promotion@gmail.com](mailto:seifert.promotion@gmail.com)
* Projekt vznikl v rámci kurzu **Datový Analytik s Pythonem** od [Engeto](https://engeto.cz/)

```



