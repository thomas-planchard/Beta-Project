# Beta-Project : Implement a Hex Board Game

![Hex Board Game](https://upload.wikimedia.org/wikipedia/commons/3/38/Hex-board-11x11-%282%29.jpg)

Your objective is to implement in C# .Net a fully functional Hex Game that allows two different players to play the game, save the results and tells if a player has won.
The board size has to be configurable.

The game has a graphical interface that allows to see the players stones, select a stone and move it. If the move is possible, then the player can move it.

If this objective is met, it is possible to add a player against computer implementation. The computer game play can be done using Min-Max or Alpha-Beta alogorithms

# Game rules :

Each player is assigned a pair of opposite sides of the board which they must try to connect by taking turns placing a stone of their color onto any empty space. 

Once placed, the stones are unable to be moved or removed. A player wins when they successfully connect their sides together through a chain of adjacent stones. 

Draws are impossible in Hex due to the topology of the game board. 
