Tic-Tac-Toe AI Project

What is this?
This is a tic-tac-toe game where you play against the computer. The AI uses different algorithms to play against you. I made this for my AI class project.

How to run it
1. You need Common Lisp installed on your computer (I used Allegro CL v11.0)
2. Open the file `tik-tak.lisp` in your Lisp environment
3. Load the file
4. Type `(start-game)` to start playing

 How to play
- The game will show you a menu with 4 options
- Pick which AI algorithm you want to play against:
  - Option 1: DFS (Depth First Search)
  - Option 2: Heuristic Search
  - Option 3: Minimax with Alpha-Beta Pruning (this one is the smartest!)
  - Option 4: Exit the game
- Enter numbers 1-9 to place your X on the board
- The AI plays as O
- Try to get 3 in a row!

 What it does
- Shows the game board
- Lets you play against AI
- Shows stats about how the AI is thinking (time, nodes visited, memory)
- Tells you the win chance after each AI move
- At the end it shows how well the AI played

 The AI algorithms
1. DFS: Uses depth-first search to find winning moves
2. Heuristic: Uses a scoring system to pick good moves
3. Minimax + Alpha-Beta: The best algorithm, it thinks ahead and plays optimally

 Notes
- The AI is pretty smart especially with Minimax
- You can play multiple games in a row
- Press 4 to exit when you're done

---
Made by: ASIM IYAD OMER 
Course: AI Fundamentals 
