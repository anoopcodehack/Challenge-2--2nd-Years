
# SOSC Round 2 challenge — 2nd Years



This repo has my solutions for the three problems given in Round 2.  
Each problem gives one clue, and in the end all clues are combined to form the final key.


 Problem 1 – Grid Rotation
 I read the 5x5 grid and the directions (L or R).
 Each row is rotated by 1 position based on the direction.
 After all rotations, I took the middle row (3rd row).
 Then I added the ASCII values of all characters in that row.

Clue 1 = 385  
Hex value = 181


 Problem 2 – String Processing
Steps -
 Reverse the string.
 Remove every 3rd character.
 Shift each character by +2 (ASCII).
 Count vowels in the final result.

Clue 2 = 4


 Problem 3 – State Machine
Rules I used:
 Even numbers move one state forward.
 Prime numbers directly jump to the final state.
 Odd composite numbers don’t move.
 I counted how many numbers end in the final state.

Clue 3 = 4


Final Key:
hex(385) = 181  
Clue 2 = 4  
Clue 3 = 4  
 "4" repeated 4 times → 4444


