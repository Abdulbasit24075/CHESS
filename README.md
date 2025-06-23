# 🧠 Chess Game

A fully functional chess game built using **C++** and **Object-Oriented Programming (OOP)** principles. This project simulates the classic game of chess with all standard rules and features implemented.

## 🎮 Features

- ✔️ Standard 8x8 chessboard
- ♟ Full support for all chess pieces and moves:
  - King, Queen, Rook, Bishop, Knight, Pawn
  - Castling
  - En Passant
  - Pawn Promotion
- 🔄 Turn-based gameplay
- 🚫 Check and Checkmate detection
- 🎨  Graphical version using [Raylib](https://www.raylib.com/) 

## 🛠 Technologies Used

- C++
- Object-Oriented Programming (OOP)
- [Raylib library](https://www.raylib.com/)

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/da097775-3a1c-430b-a09e-189db25f3411)


## 🚀 Getting Started

### Prerequisites
- C++ Compiler (Visual Studio 2022)
- Raylib library (only for graphical version)

### How to Compile and Run

```bash
g++ main.cpp -o chess -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./chess
