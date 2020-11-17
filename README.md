# price-forbes-java-test

Write a program in Java which implements Conway’s Game of Life. 

You can find the rules of the game here: ​https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

The interface to be used as a basis to implement the game has been provided.

There are two methods in the interface:

1. The seed method sets the pattern to be used in the game.

2. The next method applies the rules of the game to the pattern and returns the amended pattern – called the “next generation” in the game.  This next generation replaces the previous pattern. Each call to the next method results in a next generation and a new state (pattern).
  
Example
  
This is called an “oscillator pattern” in the game of life. The initial pattern is such that on repeated calls to the next method the pattern oscillates between two states.
  
Input (through the seed method):
  
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,1,1,1,0,0,0],
                      [0,0,0,0,0,1,1,1,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0]


Output on next:

                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,1,0,0,0,0],
                      [0,0,0,0,1,0,0,1,0,0],
                      [0,0,0,0,1,0,0,1,0,0],
                      [0,0,0,0,0,0,1,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0]

Output on next:

                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,1,1,1,0,0,0],
                      [0,0,0,0,0,1,1,1,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0],
                      [0,0,0,0,0,0,0,0,0,0]
