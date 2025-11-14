# sudoku-sage
Master sudoku intuitively in a simple game

🧩 Sudoku-Sage: A Beginner's Guide to the Game and Tools
Welcome to Advanced Sudoku! This guide will walk you through the rules, explain all the powerful tools at your disposal, and teach you the core logic you'll need to start solving puzzles like a pro.

1. The Rules of the Game
Sudoku is a logic puzzle played on a 9x9 grid. The board is divided into nine 3x3 smaller squares (called boxes).

The core rule is simple: Every row, every column, and every 3x3 box must contain all digits from 1 to 9, with no repeats.

The numbers already filled in (the givens) cannot be changed.

Your task is to fill in the empty cells using pure logic.

2. Your Sudoku Toolkit (The Four Modes)
The most important tool is the Mode Button (located above the Undo/Erase buttons). Clicking it cycles through four input states, allowing you to manage your notes and final answers.

Mode

Icon

Function

When to Use It

Value Mode

✏️

Enter a final, confirmed answer. Clears all notes in that cell automatically.

When you are 100% certain of the digit for a cell.

Corner Note Mode

✍️

Enter small pencil marks in the cell's corners (candidates).

To track potential numbers that could fit in a cell.

Center Mark Mode

⭐

Enter larger center marks (strong candidates).

To highlight strong possibilities or use specific solving techniques.

Strike Mode

🚫

Removes an entered note (both corner and center marks) from the selected cell(s).

When your logic confirms a candidate is impossible for a selected cell.

Tip: Select a cell, then press the number button (1-9) to apply the current mode's action.

3. Game Controls for Efficiency
These buttons are designed to help you manage your session, correct mistakes, and speed up note-taking.

Button

Icon

Function

Why it Helps

Undo

↩️

Reverts the last move (value input, note toggle, or clear).

Essential for quickly fixing an accidental click or testing a theory.

Erase

❌

Clears the value and all notes from all currently selected cells.

The fastest way to empty multiple cells simultaneously.

Reset

🏠

Restores the entire board to its original, starting configuration.

If you get hopelessly stuck and want to start fresh without losing the puzzle.

Auto Notes

📝

Scans the board and automatically fills corner notes for all empty cells with every mathematically possible candidate.

A massive time-saver. Eliminates the manual work of writing initial candidates.

Smart Hint

✨

Uses AI to analyze the board and provide the next logical step.

Use it when you are stuck and need a gentle push toward the solution.

Solve

🔮

Instantly fills the entire board with the correct solution.

For when you give up, or just want to confirm your final answer.

4. Essential Solving Techniques
You don't need complicated math; Sudoku relies entirely on visual logic and elimination. Start with these fundamental techniques:

A. Scanning (Simple Sweeping)

This is the easiest way to start. Scan each row, column, and 3x3 box, looking for digits 1 through 9.

Select a number (e.g., the number 4 button) to highlight all of its occurrences on the board.

Focus on an empty box. Look at the three rows and three columns that intersect that box.

If all three "lanes" (rows/columns) of the target digit (4) are blocked from entering the box, you have made a mistake! If only one cell remains open for the 4, you've found its correct position.

B. Naked Singles (The Easiest Find)

This technique uses your notes (pencil marks):

Use the Auto Notes (📝) button. This fills all candidates.

Scan the board for a cell that has only one candidate listed (e.g., only a 6 in its corner notes).

If a cell has only one possible number left, that number must be the final answer for that cell. Enter it using ✏️ Value Mode.

Once you find a final answer, use the principles of elimination to remove that number as a candidate from all other cells in the same row, column, and box. Keep repeating this process until no more Singles can be found!

Ready to apply these tools? Select New Game and let the logic begin! Do you want to try practicing the Naked Singles technique on your first puzzle?

