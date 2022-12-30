# Connect-Four-Python-Game

# Q1: Connect Four - The Board
Weight: 20%

Last update: 20 Sep, 7am

Connect four is a connection game in which two players take turns dropping discs into a (6 x 7) board, i.e., 6 rows x 7 columns. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

Check out this Wikipedia article to learn more about the game and how it is played.

In the following couple of questions, you will implement a custom version of this game that allows the players to play it on a general (r x c) sized board. For the standard size we have r=6 and c=7, where r represents the number of rows and c the number of columns on the custom board.

In this question, you will output the board of the game upon being prompted by the user for r and c. The '·' character that you see in the sample runs below will be used to indicate an empty board position. In this question players will not be able to make moves yet. 

Take a look at the sample runs below to understand what you are supposed to do. Note that you need to be able to produce the exact output shown below, including the spaces. 

Do not write too many lines of code. For your reference, our implementation has < 20 lines. 

Here are a few sample runs:
```
1:

Standard game? (y/n): y
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 

2:

Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 2
1 · · 
0 · · 
  0 1 
3:

Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 3
1 · · · 
0 · · · 
  0 1 2 
4:

Standard game? (y/n): n
r? (2 - 20): 3
c? (2 - 20): 2
2 · · 
1 · · 
0 · · 
  0 1 

5:

Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 8
4 · · · · · · · · 
3 · · · · · · · · 
2 · · · · · · · · 
1 · · · · · · · · 
0 · · · · · · · · 
  0 1 2 3 4 5 6 7 

6:

Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 13
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 

7:

Standard game? (y/n): n
r? (2 - 20): 13
c? (2 - 20): 5
12  ·  ·  ·  ·  · 
11  ·  ·  ·  ·  · 
10  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  · 
    0  1  2  3  4 
```

# Q2: Connect Four - Fancy Board
Weight: 20% 

Last update: 20 Sep, 2:40pm

You will build on top of the previous question and add an additional output option to your program in this question. You should copy your code from Q1 and add more code in this question. 

In this question, you will implement an option for a more fancy board. Take a look at the sample runs below to understand the exact requirements. 

Do not write too many lines of code. For your reference, our implementation has < 30 lines. 

Here are a few sample runs:

```

1:

Standard game? (y/n): y
Fancy board? (y/n): n
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 

2:

Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 2
Fancy board? (y/n): n
1 · · 
0 · · 
  0 1 

3:

Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 3
Fancy board? (y/n): n
1 · · · 
0 · · · 
  0 1 2 

4:

Standard game? (y/n): n
r? (2 - 20): 3
c? (2 - 20): 2
Fancy board? (y/n): n
2 · · 
1 · · 
0 · · 
  0 1 

5:

Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 8
Fancy board? (y/n): n
4 · · · · · · · · 
3 · · · · · · · · 
2 · · · · · · · · 
1 · · · · · · · · 
0 · · · · · · · · 
  0 1 2 3 4 5 6 7 

6:

Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 13
Fancy board? (y/n): n
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 

7:

Standard game? (y/n): n
r? (2 - 20): 13
c? (2 - 20): 5
Fancy board? (y/n): n
12  ·  ·  ·  ·  · 
11  ·  ·  ·  ·  · 
10  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  · 
    0  1  2  3  4 

8:

Standard game? (y/n): y
Fancy board? (y/n): y
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 

9:

Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 2
Fancy board? (y/n): y
 +-+-+
1|·|·|
 +-+-+
0|·|·|
 +-+-+
  0 1 

10:

Standard game? (y/n): n
r? (2 - 20): 2
c? (2 - 20): 3
Fancy board? (y/n): y
 +-+-+-+
1|·|·|·|
 +-+-+-+
0|·|·|·|
 +-+-+-+
  0 1 2 

11:

Standard game? (y/n): n
r? (2 - 20): 3
c? (2 - 20): 2
Fancy board? (y/n): y
 +-+-+
2|·|·|
 +-+-+
1|·|·|
 +-+-+
0|·|·|
 +-+-+
  0 1 

12:

Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 8
Fancy board? (y/n): y
 +-+-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+-+
0|·|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 7 

13:

Standard game? (y/n): n
r? (2 - 20): 5
c? (2 - 20): 13
Fancy board? (y/n): y
  +--+--+--+--+--+--+--+--+--+--+--+--+--+
 4| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·|
  +--+--+--+--+--+--+--+--+--+--+--+--+--+
 3| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·|
  +--+--+--+--+--+--+--+--+--+--+--+--+--+
 2| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·|
  +--+--+--+--+--+--+--+--+--+--+--+--+--+
 1| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·|
  +--+--+--+--+--+--+--+--+--+--+--+--+--+
 0| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·| ·|
  +--+--+--+--+--+--+--+--+--+--+--+--+--+
    0  1  2  3  4  5  6  7  8  9 10 11 12 
    
 
```

# Q3: Connect Four - Play
Weight: 20%

Last update: 20 Sep, 7am

You will build on top of the previous question and add additional functionality to your program. You may copy your code from Q2 and add more code in this question. 

You will implement the game play in this question. Players 'X' or 'O' make moves by specifying the column in which a move should be made. If a player enters 'e' the game is over and you should output 'bye'.

Initially you should output the empty board, then Player 'X' starts and the board will be printed again with the new move. 

You don't need to check if a move is legal and you may assume that all moves made are allowed and no move made is game ending.

That is, you don't have to check if the game is over (4 in a row, column or diagonal) and you don't have to check if the provided move is possible (column not full and provided column is within bounds). You will work on this in assignment 2, so don't post any code related to this to the forum. 

Do not write too many lines of code. For your reference, our implementation has < 50 lines. 

Here are a few sample runs:

```

1: 

Standard game? (y/n): y
Fancy board? (y/n): n
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): 0
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 X · · · · · · 
  0 1 2 3 4 5 6 
playerO (col #): 0
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 O · · · · · · 
0 X · · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): e
bye

2: 

Standard game? (y/n): y
Fancy board? (y/n): n
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · · · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): 1
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · · · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6 
playerO (col #): 1
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · · · · · · · 
1 · O · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6 
playerX (col #): 1
5 · · · · · · · 
4 · · · · · · · 
3 · · · · · · · 
2 · X · · · · · 
1 · O · · · · · 
0 · X · · · · · 
  0 1 2 3 4 5 6 
playerO (col #): e
bye

3: 

Standard game? (y/n): y
Fancy board? (y/n): y
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerX (col #): 0
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|X|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerO (col #): 1
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|X|O|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerX (col #): 0
 +-+-+-+-+-+-+-+
5|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
4|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
3|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
2|·|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
1|X|·|·|·|·|·|·|
 +-+-+-+-+-+-+-+
0|X|O|·|·|·|·|·|
 +-+-+-+-+-+-+-+
  0 1 2 3 4 5 6 
playerO (col #): e
bye

4: 

Standard game? (y/n): n
r? (2 - 20): 11
c? (2 - 20): 10
Fancy board? (y/n): n
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 0
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 1
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 1
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 1
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 6
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  X  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 9 
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  · 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  X 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  O 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  X 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerX (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 2  ·  O  ·  ·  ·  ·  ·  ·  ·  O 
 1  ·  X  ·  ·  ·  ·  ·  ·  ·  X 
 0  X  O  ·  ·  ·  ·  X  ·  ·  O 
    0  1  2  3  4  5  6  7  8  9 
playerO (col #): e
bye

5: 

Standard game? (y/n): n
r? (2 - 20): 11
c? (2 - 20): 13
Fancy board? (y/n): n
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 11
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 11
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  · 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  · 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): 12
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerO (col #): 9
10  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 9  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 8  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 7  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 6  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 5  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  · 
 4  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 3  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O 
 2  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  X 
 1  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  O 
 0  ·  ·  ·  ·  ·  ·  ·  ·  ·  O  ·  X  X 
    0  1  2  3  4  5  6  7  8  9 10 11 12 
playerX (col #): e
bye

```
