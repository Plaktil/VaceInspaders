# VaceInspaders

First attempt at a game coded in python using pygame.
My focus is not the playability of looks of the game but more the mechanics surrounding it.
Feel free to suggest any improvements that would make me learn something new while doing it ;)

Controls are left/right/space.

... Did not keep track of changes made before this point...

LOGS:

20/01/2022:
The game has 1 level, some sound effects, Winning and Losing ending.

Implementing a basic networking setup. To test, run the server script, then run (up to 2) clients to interact with the server.

- Only works locally for now.
- Instantiating the Network class with a local IP adress lets you connect to a remote (but local) machine.

The goal is to implement some kind of pvp over the internet (by gettin someone to run the server and giving his external IP to another consenting adult ;) ) to learn more about sockets and threads.

I was following a tutorial which used _thread which i hear is now deprecated. It is what i am using right now as i am not yet so knowledgeable about threads yet.


21/01/2022:
Creation of the PvPVaceInspader.py file to work on the pvp version without breaking the original game.

- Started defining classes to clarify the code
- Imported Network to have a n instance as an attribute for the player
- Added a second ship surface rotated 180 deg for ennemy player

22/01/2022:
After 3 attempts at refactoring, realized that this process has to be very procedural and slow paced: you create one class,
make it's __init__ and test it. Then add a couple methods and test it. Then you move on to another class.

- The code is now fully (from what i understand of it) OOP
- Now is the time to add some networking to it!