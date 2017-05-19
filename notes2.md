John typing, Anne taking notes

Pascal's triangle part two

adding test cases:
pascal(0, 0)
pascal(0, 1)

and adding a default value-- else -1 (invalid value)

the test cases run, we have base cases, what's next?
adding more tests: 
pascal(1,0)
pascal(0,2)
pascal(2, 2)

2,2 is not yet implemented

add to the if statement: if row == col return 1

now 2,2 is implemented

pascal(3, 2) // should be 3, 1 3 *3* 1

adding to the not-yet-implemented else:
else pascal(col, row) + pascal(col, row) // this is an infinite loop

else pascal(col, row - 1) + pascal(col, row - 1) // this is not an infinite loop, but is not correct

