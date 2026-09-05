# ♟️ Chess AI — Pygame Minimax

A Python-based chess game built with **Pygame**, featuring an AI opponent powered by the **Minimax algorithm with Alpha-Beta pruning**.

## ✨ Features

- ♟️ Play chess against the computer
- 🤖 Minimax-based AI opponent
- ⚡ Alpha-Beta pruning for optimized search
- 🎯 Configurable AI difficulty / search depth
- 🟢 Legal move highlighting
- ♜ Castling support
- ♙ Pawn promotion
- 🔄 En passant support
- ⚠️ Check and checkmate detection
- 🤝 Stalemate and draw detection
- 🎨 Multiple board themes
- 🔊 Game sound effects
- ↩️ Undo and restart options
- 🖥️ Interactive Pygame interface

## 🧠 AI Algorithm

The computer player uses **Minimax** to evaluate possible future positions and select a strong move.

**Alpha-Beta pruning** is used to eliminate branches that cannot affect the final decision, reducing the number of positions that need to be evaluated.

The AI evaluation considers factors such as:

- Piece values
- Piece positioning
- Board control
- Game-ending positions

## 🛠️ Technologies Used

- **Python**
- **Pygame**
- **Minimax**
- **Alpha-Beta Pruning**
- Object-Oriented Programming

## 📁 Project Structure

```text
Chess-AI-pygame-Minimax/
│
├── Minimax/
│   ├── chessAI.py
│   └── PointMap.py
│
├── pieces/
│   ├── base.py
│   ├── bishop.py
│   ├── king.py
│   ├── knight.py
│   ├── pawn.py
│   ├── queen.py
│   └── rook.py
│
├── screens/
│   ├── chess.py
│   └── menu.py
│
├── assets/
│   ├── images/
│   ├── sounds/
│   └── fonts/
│
├── board.py
├── computer.py
├── Fen.py
├── main.py
├── setting.py
├── tools.py
├── ui.py
├── utils.py
└── visualizeMaps.py
```

## 🚀 Installation

Clone the repository and install the required dependency:

```bash
pip install pygame
```

Then run:

```bash
python main.py
```

## 🎮 Controls

- Use the **mouse** to select and move pieces.
- Use the available menu options to configure the game.
- Change the board theme using the theme controls.
- Use the game controls to restart or undo moves.

## 📌 About the Project

This project demonstrates how classic game-search techniques can be applied to build a playable chess AI.

The main focus is understanding:

1. Chess board representation
2. Legal move generation
3. Position evaluation
4. Minimax game-tree search
5. Alpha-Beta pruning
6. Interactive game development with Pygame

## ⚠️ Attribution & License

This README has been reformatted for clearer documentation. The **source code, assets, and original project remain subject to their original author's license and terms**.

If you publish or redistribute this repository, review the original repository's license and retain any required attribution.
