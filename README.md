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

## CHESS THEMES

![Screenshot (367)](https://user-images.githubusercontent.com/48150537/193105513-8a35f0a1-ad84-42a5-a81c-08e7f1daae4b.png)

![Screenshot (374)](https://user-images.githubusercontent.com/48150537/193105555-1c055b48-b804-47b1-9e30-d0748390cb31.png)
![Screenshot (373)](https://user-images.githubusercontent.com/48150537/193105610-51889fd7-6489-465b-8fa8-a2eaa8927e03.png)
![Screenshot (372)](https://user-images.githubusercontent.com/48150537/193105662-7db703af-d0cf-4038-8f97-789b09c1cf5f.png)
![Screenshot (371)](https://user-images.githubusercontent.com/48150537/193105730-6b46ab4b-37a3-45a0-8692-34c659eb32c5.png)
![Screenshot (370)](https://user-images.githubusercontent.com/48150537/193105805-98833eb1-8dcd-4f7f-b6f0-419b0309b007.png)
![Screenshot (369)](https://user-images.githubusercontent.com/48150537/193105861-afb43e5b-8219-4a49-baee-d98609b97ed2.png)
![Screenshot (368)](https://user-images.githubusercontent.com/48150537/193105891-e6da0206-9338-45bd-ae7a-bd34a2ee564f.png)
