# Gomoku Game 🎮

## Overview
The **Gomoku** project is a strategic board game implemented in Python using **Object-Oriented Programming (OOP)** principles and **layered architecture**. This implementation allows players to play against a computer AI that uses strategic algorithms to block winning moves and challenge the player. The game features a user-friendly **PyGame GUI** and robust **input validation** to ensure smooth gameplay.

## Features

### 1. **Gameplay**
   - **Human vs Computer**: The game supports a one-player mode where the user can compete against an AI that strategically places pieces to block the player's winning moves and attempt to win.
   - **Strategic AI**: The AI uses basic strategies to assess the board and make its moves, making it a challenging opponent for the player.
   - **Victory Conditions**: The game follows traditional Gomoku rules, where the first player to align five consecutive pieces horizontally, vertically, or diagonally wins.

### 2. **Input Validation**
   - The game includes strict validation for user inputs to prevent errors such as placing pieces outside the board or on already occupied spaces.
   - Invalid inputs trigger error messages, ensuring that the user always receives feedback when trying to make an incorrect move.

### 3. **Graphical User Interface (GUI)**
   - Built using **PyGame**, the GUI provides an engaging and interactive experience for users.
   - The game board is displayed in a visually appealing grid, and each move is reflected in real-time as players take turns.
   - Features include buttons for restarting the game, displaying the winner, and a visual countdown for the AI’s turn.

### 4. **Testing**
   - Unit tests have been developed for all non-UI modules, ensuring high code quality and functionality.
   - Comprehensive tests cover core game logic, such as move validation, win condition checks, and AI behavior.

## Technologies Used:
- **Python** for core game logic and AI implementation.
- **PyGame** for GUI development, providing an interactive and engaging game interface.
- **Object-Oriented Programming (OOP)** to structure the code for maintainability and scalability.
- **Unit Testing** to ensure the reliability of the core game mechanics.

## Getting Started:

1. **Clone the Repository**:
`git clone https://github.com/Andreea410/Gomoku`
2. **Install Dependencies**:
Ensure that **PyGame** is installed on your system. You can install it using pip:
`pip install pygame`
3. **Run the Game**:
After installing the dependencies, you can run the game by executing the following Python file:
`python gomoku.py`

4. **Gameplay Instructions**:
- To make a move, click on an empty cell in the grid.
- The player plays as one color, and the computer automatically plays as the opposite color.
- The game will notify you of the winner or a draw when the game ends.

## Contributing:
Feel free to contribute to this project by opening issues or submitting pull requests with bug fixes, features, or improvements. Contributions are always welcome!

## License:
This project is licensed under the MIT License.

---

📧 **Contact**: andreeaungur494@yahoo.com  
🔗 **GitHub**: [Andreea410](https://github.com/Andreea410)

