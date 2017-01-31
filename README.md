# Knight's tour
Problem: you have a standard 8x8 chessboard, empty but for a single knight on some square. Your task is to emit a series of legal knight moves that result in the knight visiting every square on the chessboard exactly once. Note that it is not a requirement that the tour be "closed"; that is, the knight need not end within a single move of its start position. 

Details: http://rosettacode.org/wiki/Knight%27s_tour

##Solution
On an 8x8 board, there are plenty of closed tours (the knight ends on a square that is one knight's move from the beginning square). I used Symmetric (discovered by Carl Ferdinand von JÃ¤nisch) and, since the knight can walk by closed tour starting at any square, we can start at required point and visit every square only once

##Output
Starting in 11 (A1). Then Knight goes 23 (B3)... 

`f.i.21:1 1
11 23 31 12 24 43 35 16 28 47 66 58 77 85 73 81 62 54 46 25 17 38 57 78 86 65 84 72 51 63 55 67 88 76 68 87 75 56 64 83 71 52 33 41 22 14 26 18 37 45 53 74 82 61 42 21 13 34 15 27 48 36 44 32`

`27 48 36 44 32 11 23 31 12 24 43 35 16 28 47 66 58 77 85 73 81 62 54 46 25 17 38 57 78 86 65 84 72 51 63 55 67 88 76 68 87 75 56 64 83 71 52 33 41 22 14 26 18 37 45 53 74 82 61 42 21 13 34 15`

##Credit
Thanks to [Sa1Gur](https://github.com/Sa1Gur) for explaining Symmetric.
