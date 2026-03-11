# 🎮 Mini Game Portal: Vanilla JavaScript Game Portal

A comprehensive, interactive web portal featuring 9 fully playable browser games. This project was built entirely from scratch without the use of heavy frontend frameworks (like React or Angular) or game engines (like Unity). 

**Live Demo:** https://debasishpradhan28.github.io/Mini-games

## 💡 Why I Built This
This project serves as a practical playground to master core software engineering concepts, DOM manipulation, and state management. Instead of building standard CRUD applications, I chose to build 9 distinct games because each one presents a completely unique technical challenge:

* **Algorithmic Generation:** Using a backtracking algorithm to generate and solve highly complex Sudoku grids on the fly.
* **Physics & Game Loops:** Utilizing the HTML5 `<canvas>` API and `requestAnimationFrame` to manage real-time collision detection, projectile math, and memory garbage collection in a Space Shooter.
* **Asynchronous Data Handling:** Using the `fetch()` API and Promises to pull question data from JSON databases dynamically.
* **State & Phase Management:** Handling strict turn-based logic, timing events (`setTimeout`), and browser storage (`localStorage`) for persistent high scores.

## 🕹️ The Games

1.  **Star Fighter (Retro Space Shooter):** A canvas-based arcade shooter featuring AABB collision detection, dynamic particle explosions, and a continuous game loop.
2.  **Logic Gate Circuit:** A digital logic simulator. Route Boolean values (1s and 0s) through interactive AND, OR, and XOR gates to power the final output.
3.  **Sudoku Master:** A dynamically generated numbers puzzle featuring 5 difficulty levels, real-time error tracking, and a backtracking solver.
4.  **Snake Ultimate:** A high-speed canvas game featuring dynamic obstacles, wrapping walls, custom themes, and decaying bonus-score mechanics.
5.  **Quick Math Sprint:** A 60-second arithmetic challenge featuring dynamic equation generation, smart distractor answers, and time penalties.
6.  **Versus Card Match:** A 2-player competitive memory game utilizing CSS 3D Transforms (`rotateY`, `preserve-3d`) and responsive grid scaling up to 8x8.
7.  **Pattern Memory:** A visual recall test featuring dynamic CSS Grid generation and strict phase-state management.
8.  **Would You Rather:** A social interactive deck that dynamically fetches and renders questions from a JSON database, featuring animated CSS percentage bars.
9.  **Tic-Tac-Toe:** The classic strategy game featuring a dynamic 2D array win-checker and a custom DOM-based confetti celebration engine.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Flexbox, CSS Grid, 3D Transforms, Keyframe Animations)
* **Logic:** ES6+ Vanilla JavaScript (Classes, Async/Await, Array Methods)
* **APIs Used:** HTML5 `<canvas>`, Web Storage API (`localStorage`), Fetch API
* **Data Structure:** JSON

## 🚀 How to Run Locally

If you want to run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/web-arcade.git](https://github.com/your-username/web-arcade.git)
