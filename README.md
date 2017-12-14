# Rotation-of-a-2D-Matrix
This code presents the algorithm of how to rotate a 2D matrix

90+ rotation:
  1. transpose the input matrix
  2. reverse each row of the resultant matrix of step 1.
  
90- rotation:
  1. transpose the input matrix
  2. reverse each column of the resultant matrix of step 1.
  
Rotate by +180:
    Method 1: Rotate by +90 twice
    Method 2: Reverse each row and then reverse each column
    
Rotate by -180:
    Method 1: Rotate by -90 twice
    Method 2: Reverse each column and then reverse each row
    Method 3: Reverse by +180 as they are same    
    
if the input matrix is:
5 1 2 6
1 1 9 3
1 1 2 3
8 1 2 7


90+ rotation of the input matrix:
8 1 1 5
1 1 1 1
2 2 9 2
7 3 3 6

90- rotation of the input matrix:
6 3 3 7
2 9 2 2
1 1 1 1
5 1 1 8

180+ rotation of the input matrix:
7 2 1 8
3 2 1 1
3 9 1 1
6 2 1 5

180- rotation of the input matrix:
7 2 1 8
3 2 1 1
3 9 1 1
6 2 1 5
