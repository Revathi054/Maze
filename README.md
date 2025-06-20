# 🧩 Maze Game

A fun and interactive web-based Maze Game built using **HTML**, **CSS**, and **JavaScript** with a canvas-based visualization of a procedurally generated maze. Navigate the player from start to finish without revisiting any cell, or you'll need to restart!

## 🎮 Features

- 🎨 **Maze Generation:** Dynamic maze generated using recursive backtracking.
- 🧍 **Player Navigation:** Move using arrow keys or on-screen direction buttons.
- 🔁 **Restart Logic:** If a previously visited cell is entered, a restart message is shown.
- 🏁 **Win Detection:** Game ends successfully when the player reaches the bottom-right cell.
- ✨ **Scoreboard:** 
  - +10 points for valid moves.
  - -10 points for invalid moves (with a lower bound of 0).
- 🧠 **Solution Path Validation:** Ensures user remains within the solvable maze path.

## 📁 Project Structure

MazeGame/
│
├── index.html # Main HTML structure
├── style.css # Styling for UI elements
└── (All scripts are inline inside index.html)


## 🚀 How to Run

1. **Clone the Repository**
 
     ```bash
     git clone https://github.com/your-username/maze-game.git
     cd maze-game
2.Run in Browser



    Simply open index.html in your web browser.
    
    OR
    
    Use Live Server in VS Code
    
    Install Live Server Extension
    
    Right-click on index.html and choose "Open with Live Server"



🔧 Controls
    Start: Click the Start button to generate a new maze.



Move Player:

    Keyboard: Use ArrowUp, ArrowDown, ArrowLeft, ArrowRight
    
    Buttons: Click the corresponding Up / Down / Left / Right buttons

🏆 Scoring Rules
    +10 for each valid move.
    
    -10 for each invalid move (score cannot drop below 0).
    
    Visiting a previously visited cell ends the game and shows a restart option.


🖼️ Screenshots
![Screenshot (197)](https://github.com/user-attachments/assets/ec709a89-3f8a-4535-8d81-cbe5f6b8c8ec)
![Screenshot (198)](https://github.com/user-attachments/assets/37282ef7-9961-43cd-aaa1-2dd72ee918b2)


📌 Future Improvements
    ⏱️ Add a timer for speed-based scoring.
    
    💾 Save high scores in browser local storage.
    
    🧠 Add AI-based auto-solver visualization.
    
    🎮 Support for difficulty levels (larger maze sizes).




🤝 Contributing

    Contributions are welcome! Feel free to fork the repo and submit pull requests.


