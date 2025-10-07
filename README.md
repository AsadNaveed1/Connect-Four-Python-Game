# Connect Four Python Game

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-4D4D4D?style=for-the-badge&logo=windowsterminal&logoColor=white)
![Game](https://img.shields.io/badge/Game-FF6B6B?style=for-the-badge&logo=gameandwatch&logoColor=white)

A customizable command-line implementation of the classic Connect Four game with standard and fancy board display options.

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Game Components](#-game-components)
- [Sample Runs](#-sample-runs)
- [How to Play](#-how-to-play)
- [Project Structure](#-project-structure)

---

## 🎮 About

Connect Four is a connection game where two players take turns dropping discs into a vertical grid. The objective is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

This implementation allows players to customize the board size and choose between standard and fancy board display modes, making it more versatile than the traditional 6×7 board game.

---

## ✨ Features

- **Standard Game Mode**: Play on the classic 6×7 board
- **Custom Board Size**: Create boards ranging from 2×2 to 20×20
- **Fancy Board Display**: Option for enhanced visual board with borders
- **Two-Player Gameplay**: Alternating turns between Player X and Player O
- **Terminal-Based**: Runs entirely in the command line
- **Unicode Support**: Uses '·' character for empty positions

---

## 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/connect-four-python.git
   cd connect-four-python
   ```

2. **Ensure Python 3.x is installed**
   ```bash
   python --version
   ```

---

## 🚀 Usage

### Q1: Basic Board Display
```bash
python "Q1: Connect Four - The Board.py"
```
Displays a customizable Connect Four board without gameplay functionality.

### Q2: Fancy Board Display
```bash
python "Q2: Connect Four - Fancy Board.py"
```
Adds an option for fancy board display with borders and enhanced visuals.

### Q3: Full Gameplay
```bash
python "Q3: Connect Four - Play.py"
```
Complete game implementation with player turns and move validation.

---

## 🎯 Game Components

### Q1: Connect Four - The Board
- **Weight**: 20%
- **Purpose**: Display the game board
- **Features**:
  - Standard 6×7 board option
  - Custom board sizes (2-20 rows/columns)
  - Row and column numbering
  - Empty position markers ('·')

### Q2: Connect Four - Fancy Board
- **Weight**: 20%
- **Purpose**: Enhanced board visualization
- **Features**:
  - All features from Q1
  - Optional fancy border display
  - Grid lines using '+' and '|' characters
  - Improved readability

### Q3: Connect Four - Play
- **Weight**: 20%
- **Purpose**: Full game implementation
- **Features**:
  - All features from Q1 and Q2
  - Two-player turn-based gameplay
  - Column-based move input
  - Dynamic board updates
  - Exit option ('e' to quit)

---

## 📸 Sample Runs

### Q1: The Board - Sample Runs

<details>
<summary><b>Sample Run 1: Standard 6×7 Board</b></summary>

```
Standard game? (y/n): y
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 
```
</details>

<details>
<summary><b>Sample Run 2: Custom 2×2 Board</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 2
1 · · 
0 · · 
  0 1 
```
</details>

<details>
<summary><b>Sample Run 3: Custom 2×3 Board</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 3
1 · · · 
0 · · · 
  0 1 2 
```
</details>

<details>
<summary><b>Sample Run 4: Custom 3×2 Board</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 3
c? (2 - 20): 2
2 · · 
1 · · 
0 · · 
  0 1 
```
</details>

<details>
<summary><b>Sample Run 5: Custom 5×8 Board</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 8
4 · · · · · · · · 
3 · · · · · · · · 
2 · · · · · · · · 
1 · · · · · · · · 
0 · · · · · · · · 
  0 1 2 3 4 5 6 7 
```
</details>

<details>
<summary><b>Sample Run 6: Custom 5×13 Board (Double-digit columns)</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 13
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
```
</details>

<details>
<summary><b>Sample Run 7: Custom 13×5 Board (Double-digit rows)</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 13
c? (2 - 20): 5
12  ·  ·  ·  ·  · 
11  ·  ·  ·  ·  · 
10  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  · 
    0  1  2  3  4 
```
</details>

### Q3: Play - Gameplay Sample Runs

<details>
<summary><b>Sample Run 1: Standard Game - Quick Play</b></summary>

```
Standard game? (y/n): y
Fancy board? (y/n): n
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): 0
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 X · · · · · · 
  0 1 2 3 4 5 6 
playerO (col #): 0
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 O · · · · · · 
0 X · · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): e
bye
```
</details>

<details>
<summary><b>Sample Run 2: Standard Game - Column Stacking</b></summary>

```
Standard game? (y/n): y
Fancy board? (y/n): n
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): 1
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6 
playerO (col #): 1
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · O · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): 1
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · X · · · · · 
1 · O · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6 
playerO (col #): e
bye
```
</details>

<details>
<summary><b>Sample Run 3: Fancy Board Gameplay</b></summary>

```
Standard game? (y/n): y
Fancy board? (y/n): y
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerX (col #): 0
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|X|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerO (col #): 1
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|X|O|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerX (col #): 0
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|X|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|X|O|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerO (col #): e
bye
```
</details>

<details>
<summary><b>Sample Run 4: Custom Board 11×10 - Extended Gameplay</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 11
c? (2 - 20): 10
Fancy board? (y/n): n
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 0
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 1
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 1
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 1
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 6
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  X  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 9 
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  X 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  O 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  X 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  O 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  X 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): e
bye
```
</details>

<details>
<summary><b>Sample Run 5: Custom Board 11×13 - Full Column Stack</b></summary>

```
Standard game? (y/n): n
r? (2 - 20): 11
c? (2 - 20): 13
Fancy board? (y/n): n
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 11
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 11
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): e
bye
```
</details>

---

## 🖼️ Screenshots

### Standard Board (6×7)
```
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6
```

### Fancy Board (6×7)
```
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6
```

### Gameplay Example
```
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · X · · · · · 
1 · O · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6
playerO (col #):
```

---

## 🎲 How to Play

1. **Start the game**: Run Q3 (Play) file
2. **Choose game mode**:
   - Enter `y` for standard 6×7 board
   - Enter `n` to specify custom dimensions (2-20)
3. **Select board style**:
   - Enter `y` for fancy board with borders
   - Enter `n` for simple board
4. **Make moves**:
   - Player X goes first
   - Enter column number (0 to c-1) to drop your piece
   - Pieces fall to the lowest available position in that column
5. **Exit**: Enter `e` at any turn to quit the game

---

## 📁 Project Structure

```
connect-four-python/
│
├── Q1: Connect Four - The Board.py      # Basic board display
├── Q2: Connect Four - Fancy Board.py    # Enhanced board display
├── Q3: Connect Four - Play.py           # Full game implementation
└── README.md                             # Project documentation
```

---

## 🎓 Learning Objectives

This project demonstrates:
- String manipulation and formatting in Python
- User input handling and validation
- Dynamic grid generation and display
- Game state management
- Control flow and conditional logic
- Code modularization and progression

---


## 📄 License

This project is created for educational purposes.

---

<div align="center">

**Enjoy playing Connect Four! 🎮**

Made with ❤️ using Python

</div>