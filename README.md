# 🗼 Towers of Hanoi (with Custom Stack Implementation)

## 📚 Description

This is a terminal-based implementation of the classic **Towers of Hanoi** game in Python, featuring custom-built `Stack` and `Node` classes to manage disk movement. The game challenges the player to move all disks from the left stack to the right stack following the rules of Hanoi:

1. Move only one disk at a time  
2. Only the top disk can be moved  
3. No larger disk can be placed on top of a smaller disk  

This version tracks the user's moves and compares them to the optimal solution.

---

## 🛠️ Technologies Used

- Python 3.x  
- Object-Oriented Programming (OOP)  
- Linked List-style `Stack` and `Node` structures  
- Terminal input/output interaction

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/andre-maccarini/tower-of-hanoi-python-stacks.git

# Navigate into the project folder
cd tower-of-hanoi-python-stacks

# Run the game
python main.py
```

## 🎮 Game Flow
Asks the user how many disks to play with (minimum: 3)

Initializes the left stack with disks in descending order

Displays the optimal number of moves: 2^n - 1

Repeatedly prompts the user to move disks between stacks

Validates moves and provides feedback on invalid choices

Ends the game when all disks are successfully moved to the right stack

## 🧠 What I Learned
How to build and use a linked-list-based Stack class

How to model a game state using custom data structures

How to apply recursive logic (conceptually) in iterative play

How to create engaging terminal-based applications

## 📈 Possible Improvements
 Add recursive auto-solver to demonstrate algorithm

 Track and visualize move history

 Build a GUI version using Tkinter or Pygame

 Add difficulty levels or hints

## ✍️ Author
André Maccarini