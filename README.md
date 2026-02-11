# 🧩 Sudoku Solver (Web Version)

A fully interactive **Sudoku Solver Web Application** built using **HTML, CSS, and JavaScript**.

This project allows users to enter a Sudoku puzzle into a 9x9 grid and automatically solves it using a **Backtracking Algorithm**.

---

## 📌 Project Overview

This Sudoku Solver:

- Dynamically generates a 9x9 Sudoku grid
- Allows manual number input
- Validates duplicate entries
- Solves the puzzle using recursion and backtracking
- Displays appropriate error messages
- Includes a clear/reset option

The entire project is built in a **single HTML file** with embedded CSS and JavaScript.

---

## 🧠 Algorithm Used

### 🔁 Backtracking Algorithm

The solver works using recursion:

1. Locate an empty cell.
2. Try numbers from 1 to 9.
3. Check if the number is valid:
   - Not present in the same row
   - Not present in the same column
   - Not present in the same 3×3 box
4. If valid → move to next cell.
5. If no valid number works → backtrack.
6. Continue until solved.

This ensures all valid Sudoku puzzles can be solved.

---

## ✨ Features

- ✅ 9x9 dynamically generated grid
- ✅ Input validation
- ✅ Duplicate detection (rows, columns, 3x3 boxes)
- ✅ Backtracking-based solver
- ✅ Clear button to reset puzzle
- ✅ Error messages for:
  - Empty puzzle
  - Duplicate entries
  - No possible solution
- ✅ Responsive centered layout
- ✅ Styled 3x3 box borders
- ✅ Clean and user-friendly UI

---

## 🖥️ How It Works

- The grid is generated using JavaScript.
- Each cell is an input field limited to one digit.
- The solver function reads the grid values into a 2D array.
- Duplicate validation is performed before solving.
- A recursive function attempts to solve the puzzle.
- If successful → grid updates automatically.
- If not → an error message is shown.

---

## 🎯 Learning Outcomes

This project helped in understanding:

- DOM manipulation
- JavaScript recursion
- Backtracking algorithms
- Grid layout in CSS
- Input validation logic
- Algorithm optimization basics

---

## 🔮 Future Improvements

- Add step-by-step solving animation
- Add difficulty selector
- Add random puzzle generator
- Add timer functionality
- Add dark mode
- Improve mobile responsiveness
- Add keyboard-only navigation

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Open a Pull Request

---

## 👨‍💻 Author

Your Name - Saurabh
GitHub: https://github.com/Saurabh2662/Sudoku-Solver 
LinkedIn: https://linkedin.com/in/yourprofile  

---

