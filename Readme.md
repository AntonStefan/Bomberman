Anton Stefan 321CC
Mereu Ioan Flaviu 323CC                  2D Game BOMBERMAN
Seceleanu Andrei Daniel 321CD   



Implementation time: About 25 hours

vers2.py is the main source

Implementation details:
In order to create the game we used some specific libraries:
pygame - specific for creating games and multimedia application in Python
It provides functionality for creating graphics, handling events, playing sound and music, and other features commonly found in the game.
count - from the itertools module is a generator function that returns an iterator that produces an infinite sequence of integers, starting from a value that is passed as an argument
mixer -  a module in pygame library for loading and playing sounds and music
sys - a built-in Python module that provides access to various system-specific parameters and functions.

The game consists of two players that can place bombs along the map. It has 2 mods, Player 1 vs Player 2, or Player 1 vs Computer.

Initially we have the running menu that verifies what mod the player chose utilizing the cursoir of the mouse. If the player chose Player1 vs Player2, two people will take part at the game, first one having the buttons w,a,s,d to move and the spacebar to place bombs, and the second one the arrows and the "m" key to place bombs, but if the player chose mod2, one man will face a bot implemented to take random actions.

There are 3 bonuses that can be find inside the barrels, after they are bombed, and they are life, that gives an extra life, area, that shrinks the area, and vest that gives immunity, and you cant get across bombs that have been placed.

We have also options of the game such as pause, quit by pressing (p,q).

On the display you can also see the total score that is resulted by breaking barrels, each barrel giving you 2 points and it is also diplayed the health of the players. 
We have a marix that is used to delimtes where the players can or cant go and make the structure of the game with fences and barrels. We also implemented for each set of tastes(w,a,s,d,spacebar,arrow keys,m) their features.

When the game ends it is displayed in the terminal the winner of the game.





