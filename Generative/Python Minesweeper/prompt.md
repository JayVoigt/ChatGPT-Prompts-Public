Can you write me an implementation of Minesweeper in Python? The program should fulfill the following requirements:

Each tile should, by default, display the character "X" regardless of its type. For example, when starting a new game with a grid size of 8x8, this should be shown to the user (Figure 1):

Figure 1
```
  0 1 2 3 4 5 6 7
A X X X X X X X X
B X X X X X X X X
C X X X X X X X X
D X X X X X X X X
E X X X X X X X X
F X X X X X X X X
G X X X X X X X X
H X X X X X X X X
```

The user would then be prompted to enter a row index (A-H) and a column index (0-7). If the user selects tile B1, the board would then look like the 
following example (Figure 2):

Figure 2
```
  0 1 2 3 4 5 6 7
A X X X X X X X X
B X 1 X X X X X X
C X X X X X X X X
D X X X X X X X X
E X X X X X X X X
F X X X X X X X X
G X X X X X X X X
H X X X X X X X X
```

This example (Figure 2) indicates that the user selected a tile that is NOT a mine. The numeric value `1` shows that 1 adjacent tile contains a mine.

If the user selects a mine, which is placed on tile C2 as an example, the program should display output similar to the following example (Figure 3):

Figure 3
```
  0 1 2 3 4 5 6 7
A X X X X X X X X
B X X X X X X X X
C X X M X X X X X
D X X X X X X X X
E X X X X X X X X
F X X X X X X X X
G X X X X X X X X
H X X X X X X X X
```
