# Sudoku-Solver

This sudoku solver utilizes 3D matrices and some machine learining  to solve any size sudoku.
The way it works is very simple, the 3D matrices are used to map out the numbers(every matrix 
apart from the first is dedicated to a specific number). Then the Machine learning model, that 
is trained to spot specific patterns in the numbers checks every matrix one by one and fills in
any numbers it can, it then updates the matrices and starts over until a solution has been found.


But why and AI model and not an algorithm like Backtracking? 

 At first i wanted to make an AI model just because i wanted to get familiar with creating one
 and didn't really want to hard code an algorithm because it has been done before many times, 
 but then I had the idea that maybe a well trained model can solve sudokus of any size in P time
 (it can't).
 
 
 
This is it. You can use the code to run the solver on your system and input any kind of sudoku you want.
Have fun.
 
