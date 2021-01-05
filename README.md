# Sudoku
A simple sudoku solver using the naked single method

The solver uses 0 to represent a blank space in the sudoku. It searches the sudoku for blanks, and when it finds one:

Select the given 0

Define its row array

Define its column array

Define its box array

Define options array (1-9, the numbers that could go in the blank space)

For i = 1 to 9: if i exists in row || column || box => delete the i from the options

if there is only one non zero option => replace the zero value in the sudoku with the remaining option

Move on to next 0

Continue until there are no 0s left
