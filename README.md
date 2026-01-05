# ♟️ C++ Chess Engine (Project Archive)

### 🏆 Certification & Verification
**Status:** Completed & Awarded at GameXcelerate Hackathon (AIC RAISE).
**Verification:** See attached `Project_Certificate_Evidence.jpg` in this repository.

---

### 🛠️ Technical Architecture (Post-Project Documentation)
*Since the original source files are currently archived offline, this documentation outlines the core logic and algorithmic approach used during development.*

#### 1. Core Logic & Move Validation
The engine was built using **C++** with a focus on object-oriented modularity.
* **Board Representation:** Used a 2D array (8x8) to map board state.
* **Move Generation:** Implemented pseudo-legal move generation for each piece type (e.g., recursive checks for sliding pieces like Rooks/Bishops).
* **Validation:** A verification function checked for "King Safety" (ensuring a move doesn't leave the King in check) before finalizing the state update.

#### 2. Key Algorithms Used
* **Recursion:** Used for searching depth in move trees.
* **State Management:** Implemented a 'GameLoop' class to handle turn switching, checkmate detection, and pawn promotion.

### 📄 Reflection
This project was instrumental in transitioning my skills from Mechanical Engineering (simulation logic) to Computer Science (game logic), specifically teaching me memory management in C++.
