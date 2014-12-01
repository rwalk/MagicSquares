MagicSquares
============

Brute force search for 3x3 normal magic squares (coding demo)

Magic squares have been a mathematical curosity for millenia.  For a very complete overview of these immensely interesting objects:

https://en.wikipedia.org/wiki/Magic_square

Magic squares are are n by n grids of numbers where every row and every column sums to the same value.  Normal magic squares have the additional restriction that each cell in the grid contains a unique integer in the range from 1 to n^2.

I wrote this very simple Java program several years ago as part of a demo of a greedy algorithm approach to solving a complex constrained optimizaiton problem.  Everything you'd ever want to know about 3x3 magic squares was figured out long ago; there is even a formula to find all of them.  So this brute force method is, well, very brutish.  Nevertheless, this was a very fun little project and there are many ways this code could be extended to do something more interesting.

To run the program just compile MagicSquareSearch.java.  You'll be prompted to provide the number of random starting values to place in an initial 3x3 grid.  Choosing a small number of value makes it more likely that you will converge to a solution.

