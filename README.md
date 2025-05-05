    --- Maze Escape Game ---
    
   -Project Description-
This project is a maze escape simulation developed within the scope of CENG 202 - Data Structures course.
Players (agents) try to reach the exit point by avoiding obstacles in a randomly generated maze.  

   - Game Configuration-
When the program is running, enter the following information respectively:
-> 1. Labyrinth Width: a value between 4-20
-> 2. Labyrinth Height: a value between 4-20 
-> 3. Number of Agents: a value between 1-5
-> 4. Maximum Number of Rounds: a value between 10-200
     
   - Game Controls-
 Select an option from the menu for agents in each round:
example:
   Labirent genişliğini (width) girin: 8
   Labirent yüksekliğini (height) girin: 8
   Ajan sayisini (numAgents) girin: 4
   Maksimum tur sayisini (maxTurns) girin: 100

   -Game Rules-
-> Walls (W): Impassable
-> Traps (T): Moves back 2 moves when pressed on
-> Power-ups (P): Gives teleportation ability
-> Exit (G): The goal to be achieved
example:
E E E W E E T E 
E A W W E W E E 
P E E E W P E W 
E E T W T W E G 
E E E T T E E E 
E P T W E E E E 
E E E E E E E E 
T W E E E E E E 
Agent queue: Agent1 Agent2 Agent3 Agent4 
Max turns = 100

Agent1 (move/wait/power up): MOVE
Yön (UP/DOWN/LEFT/RIGHT): RIGHT

   -Exit-
The game ends in the following situations:
-> When an agent reaches the exit
-> When the maximum number of rounds is exceeded
-> When all the agents reach the exit
