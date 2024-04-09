 


https://www.tinkercad.com/things/lU2GVL9V7kp-flappy-bird/editel?sharecode=XO0E6C_ejpoLxUCcM7HCUxxKVvmUbXhFAZQHtJyHBxQ

EXPLANATION:

First we initialise the LCD, and configure the Arduino to take in the input of the potentiometer to control the flabby bird
The obstacle course is stored as strings, and looped through substrings in intervals of  (0,15) (1,16) (2,17) and so on, to give the feeling of moving forward. To control the bird/player, we print the bird on to the lcd based on the potentiometer value. If higher than half of max value, print character on top row, else bottom row. 
Lastly, to function as a game, if the position corresponding to the player and a “*” from the obstacle course coincide, the game is lost. If the obstacle course if over, you win the game!
