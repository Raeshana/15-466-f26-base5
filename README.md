# Push and Shove

Author: Raeshana Sookhoo

Design: Player movement is restricted along one axis.

Networking: A server is responsible for sharing the game state between clients.
Even-numbered clients set their isVertical flag to true, indicating to ignore horizontal input for this player.
The opposite occurs for odd-numbered clients.
The game state stores a bool, allPayersAtExit, which 'ands' all the clients' atExit to determine if the game is won. 

Screen Shot:

![Screen Shot](screenshot-1.png)

How To Play:

This game is ideally a 2-player game (but can work with more).
Even-numbered players can move vertically.
Odd-numbered players can move horizontally.
Align your players in such a way that you can push and shove each other to the exit area.

Sources: (TODO: list a source URL for any assets you did not create yourself. Make sure you have a license for the asset.)

This game was built with [NEST](NEST.md).

