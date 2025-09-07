# 🎴 Memory Game (Java Console Version)

A simple **console-based Memory Game** written in Java.  
The game shuffles pairs of cards (A, B, C, D) and lets the player flip two at a time, trying to match pairs.  
When all pairs are matched, the player wins! 🎉

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/MemoryGame.git
   cd MemoryGame
   ```

2. **Compile the program**
   ```bash
   javac MemoryGame.java
   ```

3. **Run the game**
   ```bash
   java MemoryGame
   ```

---

## 🎮 Game Instructions
- The board starts hidden with 8 cards (4 pairs).
- Enter the index of the card you want to flip.
- Try to match pairs — if they don’t match, the cards flip back.
- Continue until you find all 4 pairs.

---

## 📌 Example Gameplay
```
Welcome to the Memory Game!
|   |   |   |   |   |   |   |   |
Enter index of first card to flip: 0
| A |   |   |   |   |   |   |   |
Enter index of second card to flip: 3
| A |   |   | B |   |   |   |   |
Sorry, those cards don't match.
...
Congratulations, you won!
```

---

## 🛠️ Features
- Random shuffle of cards every game.
- Simple text-based interface.
- Input validation (prevents flipping the same card twice).

---

## 📂 Project Structure
```
MemoryGame/
│
├── MemoryGame.java   # Main game file
└── README.md         # Project documentation



## 📜 License
This project is open-source and available under the **MIT License**.
