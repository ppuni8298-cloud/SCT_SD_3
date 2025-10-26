📘 Project Description
This project is part of the SkillCraft Technology Internship Task 03.
The objective is to create a Python program that automatically solves Sudoku puzzles.
It takes an unsolved Sudoku grid as input and fills in all missing numbers using an algorithmic approach.




⚙ How It Works
The program uses a Backtracking Algorithm, which tries placing numbers 1–9 in empty cells and checks if they follow Sudoku rules:
Each row must contain digits 1–9 without repetition.
Each column must contain digits 1–9 without repetition.
Each 3×3 subgrid must contain digits 1–9 without repetition.
If a number placement leads to an invalid solution, the algorithm “backtracks” and tries another number.
