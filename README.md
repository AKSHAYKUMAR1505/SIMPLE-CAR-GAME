# SIMPLE-CAR-GAME
This is a simple car game where the player escapes from the enemy cars...

**OVERVIEW:**
A SIMPLE CAR GAME WHERE THE PLAYER CONTROLS A CAR.
THE AIM IS TO ESCAPE FROM THE ENEMY CARS IN THE MIDDLE OF THE GAME
THE GAME CALCULATES THE GAME SCORE AS CROSSES THE ENEMY CAR.

**HOW TO PLAY THE GAME:**
BASICALLY THE GAME IS ABOUT THE SURVIVAL 
THERE ARE CONTROLS AS 1 2 3 4 TO MAKE THE PLAYER’S CAR   MOVE OR ESCAPE TO RESPECTIVE LANES.
WHILE RACING THE ENEMY CAR RANDOMLY APPEARS ON THE SCREEN WHICH MOVES FROM LEFT TO RIGHT 
IF THE PLAYER’S CAR CRASHES WITH A RANDOMLY APPEARED ENEMY CAR THEN THE GAME IS STOPPED 
FOR EVERY OVERTAKE THE ENEMY CAR PLAYER GETS THE POINT 
AFTER GETTING CRASHED THEN THE SCORE TILL WILL BE THE PLAYER’S FINAL SCORE.

**EXPLAINATION OF EACH FILES:**
**Main.jack**
This file basically contains the things which are present on the screen while gaming
As it displays our team project title 
It displays time taken by the player
It also displays the no of lives remain by the player
**ControlGame.jack**
It contain the logic and implementation of what to do according to the key pressed
It also contain the logic of life of player remaining to play
It also contain the logic to run the entire game 
**Road.jack**
It contain the implementation of road 
It also contain the logic of moving road.
It contain the logic of erasing road
**Truck.jack**
It contain the implementation and the logic of enenmy car that is truck
It contain the logic behind generating the truck when a new life comes to the player
And it contain logic of erasing the truck
