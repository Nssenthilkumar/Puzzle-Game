Game Name:Puzzle Game

Developed By: 
Logesh S S,
Sudharsan K,
Senthil Kumar N S

This game was developed using HTML,CSS,and Javascript.

Game Rule:
1. slide the title around
2. Until thy are in numerical order with the empty slide in the bottom right.
3. you can change the numberical order, it it seems simple.

Implementation Algorithm
 
1. Eachsquarewill have non-editable number from 1 to 15 and an empty square.
2. A square can possibly move only in four directions left, right, top, bottom with respect to the empty square position.
3. Empty squares if available in corner both in x and y -(0,0), (0,3), (3,0) (3,3) will have two adjacent squares possibly to move.
4. Else if empty squares on corner in x or y-(0,1), (0,2), (1,0),(2,0),  (3,1), (3,2), (1,3), (2,3) will have three adjacent squares possibly to move.
5. Else if empty squares on center (1,1),(1,2),(2,1),(2,2) will have four adjacent squares to move.
6. Game ends if 1 occurs on (0,0) and 2 occurs on (0,1) and … so on.

